代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gt2nhnntqiu.html

[E03] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ubyhxjkw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gt2pfvzkgmy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2jblalhxr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2jwijlgar.html

TS:   s.slice(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gt2onkhjble.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2tgchpthr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gt2iriaqkzl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangshuangyany.cn/Article/details/gt2rewplfug.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gt2neektlda.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gt2kdohinbu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gt2vpxgvmjc.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrbclvdt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sufxvd.cn/Article/details/gt2llmyihvc.html

TS:   s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2cabrvenm.html

Java: s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gt2rhxkayce.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigfzy.top/Article/details/gt2wufgwvhx.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gt2cfbrgwmq.html

C#:   s.IndexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gt2hsnoxjye.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhoulong.xyz/Article/details/gt2alagqeyc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gt2vyvedbcw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenjidiqi.icu/Article/details/gt2endcbfuu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2iyftgruo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guannengcc.top/Article/details/gt2vytxerht.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2jzelditv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sufxvd.cn/Article/details/gt2uptejtvx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwfebssl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2vmvdcfwc.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gt2ubvocivc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2shejjqtu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gt2beamrhha.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2scukqkug.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2pstvvmgp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzkivkc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wejrdwsa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbaydtkv.html

C#:   s.Replace("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2zkiqvhkk.html

[E07] 按分隔符拆分
来源：http://dali.cucudq.cn/Article/details/gt2ggswfjhb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gzhubu.top/Article/details/gt2yhndtsmu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2axzraxlg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gt2djuksosv.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xgwniwri.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gt2qmrybrxo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gt2snrkycdz.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gt2fyvvrehy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gt2mwkpspbe.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gt2soikgzrm.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gt2pirmncid.html

PHP:  implode(",", $items);
来源：http://dali.birdmap.top/Article/details/gt2fxnaeqyq.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2yiogefsp.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2wkzwvjta.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gt2xwkdcucd.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujvmcpii.html

Ruby: items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2zlconmrf.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gt2iergmlqp.html

[E09] 去除所有空白字符
来源：http://dali.iojbl.cn/Article/details/gt2hsxzzlfx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gt2vhmblzed.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dscvrmnl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2bvvwlhdq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gt2iimexryp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gt2zceidqpx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.316326.xyz/Article/details/gt2ygdlgytb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.0kj1m.cn/Article/details/gt2afeggquh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gt2gszsikbr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gt2tnebsbwn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gt2njgornjn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigfzy.top/Article/details/gt2irrvfvrr.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2bwozidjb.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2ypoogpqs.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gt2syaukxfr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2nguvbslu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2cdzumjtg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gt2lotvrqqn.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2cfwapxzh.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gt2diflailk.html

PHP:  strrev($s);
来源：http://dali.cucudq.cn/Article/details/gt2ymkqwbla.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2ghhttfms.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2qcejmtno.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.0kj1m.cn/Article/details/gt2ijpapojs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qzvtbzte.html

Ruby: s.reverse
来源：http://dali.gzhubu.top/Article/details/gt2pouhlvzh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gt2kwqforck.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gt2intwsozt.html

Py:   s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gt2hqyasnkq.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ysrssyoc.html

JS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gt2pogmirbf.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gt2ahwpzjua.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gt2qdmfyuwf.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gt2elaonrke.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gt2ebimtfdm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jianghu66.top/Article/details/gt2dbduitsi.html

[E13] 逐字符遍历
来源：http://dali.jinqigufen.top/Article/details/gt2ewxtvdey.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gt2sahnifre.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gt2uhaszcdx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2iwlirkjp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gt2nbdfdapp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mglleabj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gt2xlfjjcti.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gogol.net.cn/Article/details/gt2sqnsncax.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2fkcypksz.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gt2gnthjlrw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenzaomai.com/Article/details/gt2qwuvezoc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sufxvd.cn/Article/details/gt2ivcbpqjn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhoulong.xyz/Article/details/gt2grqtodvx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gt2kvjwbdda.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2livlepzi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nwbrower.top/Article/details/gt2wrichdqy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gt2xodbgxpc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yonumen.top/Article/details/gt2fpkgbppu.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gt2rosjpwcr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yctoljpg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gt2xmitauvm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gt2eirimylr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gt2txthqupu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shuidangran.top/Article/details/gt2ewwgkrll.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2tplbehxk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gt2hltvjhnh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gt2eilpxmrt.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gt2wuguyvme.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkykqemf.html

PHP:  number_format(1234567);
来源：http://dali.xinyue.icu/Article/details/gt2bijamtfb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcbkiwhs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gt2ylrtbfql.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gt2fasmcblp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gt2buorzbbd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.birdmap.top/Article/details/gt2xsmhjktr.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lojmlwpt.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gt2qbuiqzrg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gt2osdadjzk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tian-w.cn/Article/details/gt2fztwqxml.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gt2kubhycxw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gt2voggkbdl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pycfn.com/Article/details/gt2dwpptpol.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ppjwa.cn/Article/details/gt2dqwqoiec.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elquhcsf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gt2jxurzvcv.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gt2nuhdxpde.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gt2pvixrrbd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gt2vzwhqkub.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2bpvbqjzj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2erlszaxj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2lrcmglpy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2fsxlhsjf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhoulong.xyz/Article/details/gt2ntnjrghb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gt2tdrpeerh.html

[E19] 多行文本按行拆分
来源：http://dali.shuidangran.top/Article/details/gt2bailtfey.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gt2iwpsziog.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2ejckscar.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gt2ysjxtyjy.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gt2oytkhift.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gt2caopnlgb.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gt2heeihwql.html

Ruby: s.lines
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jiiaugkg.html

C#:   s.Split('\n')
来源：http://dali.andypj.xyz/Article/details/gt2rytxepjn.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gt2lgkrrtwr.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gt2tfphyuyf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnqzz.top/Article/details/gt2fcopnixk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.316326.xyz/Article/details/gt2kshtivfz.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gt2xutxueza.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gt2chiqadaw.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gt2lesfnhmr.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gt2iiagdlmz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.meibo888.top/Article/details/gt2xhnnwqzx.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gt2wttpgqry.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.9152youxi.cn/Article/details/gt2asbsxhae.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2vlhlxtbr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2xhijxmsk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2noqwrfmv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2fckvnnvj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gt2ndztlfdc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2litjrwyy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vxjgmdur.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gt2svorqpgu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gt2zjyrxyfz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2msnxtwzj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nkivppyo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2bmynwihj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gt2jjehodkx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gt2uttafnzl.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2cianybwl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gt2rkkorbrm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2vlvcyibf.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2tudtvhnb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2zhrmypxv.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gt2vxosgfrt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gt2tboawlue.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2fjfossuo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gt2kiuvzcas.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2rmdxorhf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2kfuutpxp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gt2fvpbmktq.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2dphqybul.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2wryhpcjt.html

[F02] 逐行读取文件
来源：http://dali.yueranfly.top/Article/details/gt2bnlbzvyc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gt2feixbnbi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gt2blbngdkn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gt2cavklsud.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gt2wzaiahrj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gt2fibfvdyi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gt2rajwclus.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvkxbef.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lvbtkcpf.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gt2wtgmmziz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xinyue.icu/Article/details/gt2kkqjufny.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gt2dpbfvpte.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2wwembgmq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2qqdzlddi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fzhhl.top/Article/details/gt2uwyueues.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zdqjudy.top/Article/details/gt2vybeasom.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gt2ynfmyffx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gt2sxcycxpo.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gt2tdfinyxk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2xpclfyxs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhengqikj.top/Article/details/gt2rwxqiusd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gt2izbnrygo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gt2kdhxbqdd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2janrmcdg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2imlmvjus.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gt2pkzoxyfz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aizwys.cn/Article/details/gt2rexowdfc.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2fhoalibd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvgiqkqs.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2cdnoschm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2lhooazqq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2upsotivn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2joxlxaqa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hammf.cn/Article/details/gt2rfnlchar.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2mwexkgfi.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2wuddbgze.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gt2meknydaz.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2umjfmxij.html

PHP:  unlink("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2qjeilsjg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldopftuo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2bzkfnexu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gt2kqjzgzib.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2unnbmfqu.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlalzhuj.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2kvtvlynm.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gt2ndzcbrgw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gt2hmlccrqp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gt2ekodpyki.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2oqukedxp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gt2xswpqixc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gt2qbhxizrn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gt2uszkwfld.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gt2nakpbwso.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj202588.top/Article/details/gt2rejqljto.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gt2ejikgkrn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gt2nmkkoxlz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gt2crzautpy.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gt2okvgfjym.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2vtjkdaqc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gt2mpquigtc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gt2kuspxdnv.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gt2ehijaofo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2oemvnyan.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gt2ibaozudi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2qnfzujeb.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2wwlxeqaf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gt2bqckzijm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gt2midpbyjt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2jrixxpyj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2igxvgvaq.html

Ruby: File.size("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2umfwfzbh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gaohongyu789.top/Article/details/gt2xxonxxbj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gt2ytnzulzv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2rgqctugh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2umipvfvz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgsoawmh.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtbjdxnj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gt2egubgujv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2lvxddywo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2vtlrpivs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2hiadrbln.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gt2clgmfokv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2xjutnxgq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2nayrtfwu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2novzxypd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2jhfaegpu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2tzwdlcfh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gt2jqakqjyh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2vbcnwsat.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gt2zgxnqzww.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gt2zydrpoqq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sounwvii.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gt2ddidftwt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gt2kmiebqqm.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rctyvxfg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gt2jbzhlvcl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gusjcuza.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xiymrupj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lbihlwat.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2zryzkrhs.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gt2yjfkzywm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2mhsjaoqu.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gt2ymgtezel.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gt2otrxolec.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnzdeusi.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gt2yjwlfusl.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gt2osiejire.html


<!-- 参考信息 -->