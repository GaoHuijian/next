{"title":"Footer","meta":{"title":"Footer","description":"\n<p>Passing custom footer with <code>footerRender</code>.</p>\n","order":"11"},"codes":{"jsx":"import { DatePicker } from '@alifd/next';\n\nconst { RangePicker } = DatePicker;\n\nfunction footerRender() {\n    return <div className=\"custom-footer\">👍 Some useful info here</div>;\n}\n\nReactDOM.render(<div>\n    <DatePicker footerRender={footerRender}  />&nbsp;&nbsp;\n    <RangePicker footerRender={footerRender} />\n</div>, mountNode);\n","css":".custom-footer {\n    padding: 12px;\n    font-size: 12px;\n    border-top: 1px solid #DCDEE3;\n}\n"},"body":"\n````jsx\nimport { DatePicker } from '@alifd/next';\n\nconst { RangePicker } = DatePicker;\n\nfunction footerRender() {\n    return <div className=\"custom-footer\">👍 Some useful info here</div>;\n}\n\nReactDOM.render(<div>\n    <DatePicker footerRender={footerRender}  />&nbsp;&nbsp;\n    <RangePicker footerRender={footerRender} />\n</div>, mountNode);\n````\n\n````css\n.custom-footer {\n    padding: 12px;\n    font-size: 12px;\n    border-top: 1px solid #DCDEE3;\n}\n````","html":"<script>(function(){\"use strict\";\n\nvar _next = require(\"@alifd/next\");\n\nvar RangePicker = _next.DatePicker.RangePicker;\n\n\nfunction footerRender() {\n    return React.createElement(\n        \"div\",\n        { className: \"custom-footer\" },\n        \"\\uD83D\\uDC4D Some useful info here\"\n    );\n}\n\nReactDOM.render(React.createElement(\n    \"div\",\n    null,\n    React.createElement(_next.DatePicker, { footerRender: footerRender }),\n    \"\\xA0\\xA0\",\n    React.createElement(RangePicker, { footerRender: footerRender })\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> DatePicker <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">const</span> <span class=\"token punctuation\">{</span> RangePicker <span class=\"token punctuation\">}</span> <span class=\"token operator\">=</span> DatePicker<span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">function</span> <span class=\"token function\">footerRender</span><span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token punctuation\">{</span>\n    <span class=\"token keyword\">return</span> <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>custom-footer<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">👍 Some useful info here</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>DatePicker</span> <span class=\"token attr-name\">footerRender</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>footerRender<span class=\"token punctuation\">}</span></span>  <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">&amp;nbsp;&amp;nbsp;\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>RangePicker</span> <span class=\"token attr-name\">footerRender</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>footerRender<span class=\"token punctuation\">}</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div><style type=\"text/css\">.custom-footer {\n    padding: 12px;\n    font-size: 12px;\n    border-top: 1px solid #DCDEE3;\n}</style><div class=\"highlight\"><pre class=\"language-css\"><code class=\"language-css\"><span class=\"token selector\">.custom-footer</span> <span class=\"token punctuation\">{</span>\n    <span class=\"token property\">padding</span><span class=\"token punctuation\">:</span> 12px<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">font-size</span><span class=\"token punctuation\">:</span> 12px<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">border-top</span><span class=\"token punctuation\">:</span> 1px solid #DCDEE3<span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span></code></pre></div>"}