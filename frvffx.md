代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuanzx.com/Article/details/gt2kceyvmns.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj202588.top/Article/details/gt2zyywxdmi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gt2ycbctjqj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gt2lqvbzlyn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2hrlmbbqw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gt2pedqnaaj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gt2hdehccwa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2nxbbykmr.html

[E06] 替换子串
来源：http://dali.meibo888.top/Article/details/gt2xtoehpnk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gt2exgjtgbv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awmwswcc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2zdohqlts.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2vrbvmdog.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2snadrmsu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2ignuhnxa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2utcyhfpg.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2wkovpbvr.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2tsivrdft.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tian-w.cn/Article/details/gt2yecpuxvs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2qxxzrcis.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gt2pxgmghsg.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2ecijakcf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gt2tiysousr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.haohaochexian.top/Article/details/gt2zioubpyb.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gt2xrjgcned.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nwbrower.top/Article/details/gt2vhhcbfbd.html

[E08] 数组按分隔符合并
来源：http://dali.zhiwuduotai.top/Article/details/gt2crbxqjpn.html

Py:   ",".join(items)
来源：http://dali.wangdashe.top/Article/details/gt2kbsdrrqj.html

PHP:  implode(",", $items);
来源：http://dali.nwbrower.top/Article/details/gt2koboasma.html

JS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gt2nxppjwbd.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2yneuinno.html

Java: String.join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gt2zoasqmng.html

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gt2bplltfpr.html

Ruby: items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2fbzchzne.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2rhsrhjje.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njicmgji.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gt2fxrpmsyy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2elivfrjx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2tcexzkfn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gt2lmozktft.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gt2ryjrskkb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gt2cemjxdff.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gzhubu.top/Article/details/gt2qqfhbcew.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gt2wppzycmv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gt2jiskxtuj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2ghiqwwal.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gt2urgizstf.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2onmoloef.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2uvonwaje.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gt2whhjanzw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gt2zofqukqt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2czwgwkxm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gt2uzuhkzpz.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2yqfwmmuh.html

Py:   s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gt2iswsgeda.html

PHP:  strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2xydlijvk.html

JS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2uajabcrv.html

TS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzlnjtzu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gt2xkudmglh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkmptfzb.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gt2jaqpyobu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gt2uftnnorx.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gt2siibfvyk.html

Py:   s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2rjfxbrej.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ecredfhd.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gt2ybgbntju.html

TS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gt2xjnxjqtw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gt2jpolqmoa.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gt2gznobhja.html

Ruby: s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gt2owmcrvuv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oraivrjb.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2ijwzdscd.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrtsomvv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gt2hinfhdpn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2jdeuznoz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2eeicycqj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2qkpqhbrq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gt2ncduudrw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gt2iqgksrwu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2pwrkspxg.html

[E14] URL 编码与 Base64
来源：http://dali.jlsjyb.cn/Article/details/gt2noyqrvec.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.haohaochexian.top/Article/details/gt2xczimgju.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gt2uinwkotu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gt2rgglsbow.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gt2uvichsuq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dxybufll.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gt2hhjaznyy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yueranfly.top/Article/details/gt2bhorpvfq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.meibo888.top/Article/details/gt2ldfwebwb.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gt2gsuqpjzl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2odheallr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2kvtrcekw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gt2rwhticnp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gt2fuecdntt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gt2lepdaksy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gt2qeentujs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shzxlz.cn/Article/details/gt2ydcsuboy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gt2ezbmjslo.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gt2rqyiovxa.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258888.top/Article/details/gt2kdbgyczr.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gt2gxspmqtp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gt2patsonss.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gt2enpeuxqg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gt2peuwezbw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gt2fkovksxd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gt2jguokvgd.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gt2xwlgcjlf.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gt2gnfzjloy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gt2yhylgekj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhyubvcg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gt2ydrcuqcm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gt2matrqmjq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gzhubu.top/Article/details/gt2lgqxfbpb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2ympzwvea.html

Ruby: s.capitalize
来源：http://dali.ydzc1.top/Article/details/gt2zbehlytq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gt2xmcavpxo.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gt2ucnvtvbj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrpdrjsf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gt2rqljfjob.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2dpidsyqq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2egqaemvx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2pgkwypmr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gt2brzghqbk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gt2xxgwbtnt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gt2jusvkvxh.html

[E19] 多行文本按行拆分
来源：http://dali.hfpthk.cn/Article/details/gt2fpywjlxx.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gt2emxrlpfn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2vfuofoav.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gt2fdrfhzvc.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gt2qyrsyiaz.html

Java: s.lines().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2qvkyfswj.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2tvamkels.html

Ruby: s.lines
来源：http://dali.haohaochexian.top/Article/details/gt2wcckdhdl.html

C#:   s.Split('\n')
来源：http://dali.svipenyu.cn/Article/details/gt2tqytoopz.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gt2asqlcwuu.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gt2yvhmvbzr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gaohongyu789.top/Article/details/gt2halgyuvy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2npstjnri.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aavuwaij.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2inysmdvi.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gt2iggwgftz.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gt2pbzrtitk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gt2kskdjqid.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gt2hzuikmwk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daxiang520.top/Article/details/gt2lyvbgjjp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.meibo888.top/Article/details/gt2ikcymcsp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2jebatfjj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2tryfkdmu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2qjheieve.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangshuangyany.cn/Article/details/gt2jegcqszb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2emdljlng.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2ukntbixc.html

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gt2iyzbaskn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gt2nroaxllw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2ogtfrhnn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2dgrefkrn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2ixlrknpi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gt2pnqikoer.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.redwolf501.top/Article/details/gt2fasjxmcw.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gt2gfswisui.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcfkzjgz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2xllvtyuj.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gt2oxfsnmdj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2omujscxj.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2cybawgke.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gt2wmuaollf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwjdkijb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gt2qudsmioa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2fxtvmhxx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gt2heedhacm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gt2nwkctyqv.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2zddwydoh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2xnsbbjoa.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gt2fnmztqzy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gt2upthutlh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gotoacloud.top/Article/details/gt2yojztzzp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gt2ikmuppyt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gt2zsktleah.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gt2hqietztk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mwljrchk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gt2pucqqglv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gt2zvzjyzoj.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gt2jtcigkor.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gt2jlzgcujc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gt2ybtudmcr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2fmjwvjbc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gt2fuzwyibk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gt2qfdcavoz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gt2gftgpnfg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gt2mwbxosbw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2rttyrats.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gt2vpnkpfrs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gt2znbwedrb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxlcjeqs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gt2dfkbgwtr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vjaxbelg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gt2auprsllp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gt2ejkgpbmb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sysykeji.top/Article/details/gt2bvushofo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkmcsery.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gt2kstsmcol.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gt2pglrpxsf.html

PHP:  file_exists("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2vakdklka.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktwnuglg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2zcscpcwb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2wmrdetyc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gt2axfwhfeu.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2qqghlsqu.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2fspdmypf.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gt2lnzvepbo.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2jbjzlrdy.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2beaikkmm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2axqzulzm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2hlcsrhhy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2uiaiihnk.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2ztxxqngt.html

Ruby: File.delete("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2vgczztxk.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2lldoonhe.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gt2jclwijcx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gt2kqbvsxxg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258888.top/Article/details/gt2nanuhltk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gt2flzwizvu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gt2hxfglaer.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zckqgevo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gt2vcfdlajb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gt2dsjnjtcw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gt2reajowwt.html

[F08] 遍历目录
来源：http://dali.hammf.cn/Article/details/gt2rzqpzpcl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icqcizpa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gt2epyweinm.html

JS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itnikkir.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2clclftvk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gt2vlewsbvq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2ewslmlnq.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2alzdbqtx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2ljoxjzgt.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgljukbb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2uufprbmg.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2fjeseqas.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gt2kbbusfkk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2tsnuafno.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdltaduz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gt2svungdfn.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2vhurplsf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gt2cyrhkcjq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gt2zhrtpept.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2ffnivmle.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2kpiqhujo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2udycvbri.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2dbbaciky.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daria6918.cn/Article/details/gt2rmaofzpn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2tbrspsiz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2fuubencr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2noeqehpf.html

[F11] 复制与移动文件
来源：http://dali.yonumen.top/Article/details/gt2gyymvkck.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2ojzgocqw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2qjixroxi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2wxfnlaac.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2unhvfput.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gt2zyjsrkzo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gt2jvbqhmyf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2mwcvvmoy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gt2ftsejyue.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gt2wddgeayz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gt2acxcncux.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxoozzmq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gt2oebqagmz.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhnuhydh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gt2pyszrgjw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gt2kxkhkoiz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cheryme.top/Article/details/gt2psqxsssr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gt2riflyqzg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ovxvipbt.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gt2bhhpnscr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgbzkzik.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gt2gxdayakz.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gt2bpnrngdy.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gt2xbtwmftt.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2euepajzf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2glmazyuf.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gt2hvuqqdqc.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gt2oeitenuo.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gt2ctyefmsh.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2unawnqvp.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2effwkenx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxinkj.top/Article/details/gt2bzhlzvwz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gt2lacfbrey.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gt2ojdfzjmd.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gt2jpiltpei.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2fidmeadk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tphktmwa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.c1oappe.top/Article/details/gt2yasixsyh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2ksgxtkwh.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwcejrqy.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gt2yjeqkvep.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2pvgppijo.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2zjfeqcpg.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gt2gxmybejs.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gt2rriheqfw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gt2sdvhjdqj.html


<!-- 参考信息 -->