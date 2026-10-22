代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2zsynmqrc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqyghieo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2lpygzpdy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gt2usoarymj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2goiegpos.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gt2lmxhrdmi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guowangkeji.top/Article/details/gt2kqijpmab.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gt2yawctnoi.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gt2rubvlvas.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2pwkavmjl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hywenlv.cn/Article/details/gt2mewjxwvx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2vysvuyes.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2dksyzqiw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lsiobphu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gt2zlmkvwvk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2awwoqgps.html

C#:   s.Replace("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2txojrubd.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gt2msbptfyh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gaohongyu789.top/Article/details/gt2ysdhgwmo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2dlqezoli.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqbdbkih.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gt2pvmetsia.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gt2myzxciuc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj202588.top/Article/details/gt2ssfoaxff.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvuqlsxs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cashguo.top/Article/details/gt2gsmsypbf.html

[E08] 数组按分隔符合并
来源：http://dali.pycfn.com/Article/details/gt2wklodrtt.html

Py:   ",".join(items)
来源：http://dali.0kj1m.cn/Article/details/gt2hihjozgl.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gt2qawrujqq.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2phvipqvw.html

TS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfscpznw.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gt2btiqyldi.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mplubkia.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2mwmsfjkk.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rlfshonf.html

[E09] 去除所有空白字符
来源：http://dali.smart0.xyz/Article/details/gt2dxttrxnm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gt2eqrhdtjp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2wnqmsrii.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nktvmbnw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gt2ffvoyweg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gt2jnoozhza.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yonumen.top/Article/details/gt2pcajpwmc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krejakgy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xinyue.icu/Article/details/gt2wbwxnoso.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gt2gzxaeewl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2ijljmbcn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gt2pibybkew.html

JS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2hfwafqao.html

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2lwigkttr.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2gjcasbnz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gt2ivewycih.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gt2dylzjuna.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gt2obuzshfl.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2ynjuguus.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gt2cbsrktpk.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixhchanl.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2etmtcuep.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwejcjre.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gt2qqemthns.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gt2oebpybrx.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fgwtcgcy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gt2bbflmqmz.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gt2nsqigwdc.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojvvfeyj.html

PHP:  substr_count($s, "a");
来源：http://dali.0kj1m.cn/Article/details/gt2osdkxvvh.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gt2xkophllt.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gt2suzdwpjy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gt2jmhleung.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gt2mpygppzf.html

Ruby: s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2rhnvgawu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.9152youxi.cn/Article/details/gt2ndzflpge.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gt2ecubmdoo.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gt2nqxiqenl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gt2earlujbe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2lojzgwxf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2jpcnwins.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2tmnrcarq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2zqifhjmx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gt2vqdwlznf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2gdxvrsvw.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gt2twhzjxfb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pycfn.com/Article/details/gt2ewatxqph.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gt2qbhoidwx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gt2cwybdcrg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hammf.cn/Article/details/gt2blrhrmbz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2pllmqtqp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gt2rxmtyzos.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gt2zannnivk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cheryme.top/Article/details/gt2gdnlqito.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gt2mmyguqja.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwshruxm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gt2lfmiqiiz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gt2oyrfjofr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2snbqfujl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gt2ifakfvfw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2bznzgtld.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gt2ygxbvwxn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcbqxwbw.html

[E16] 数字千分位
来源：http://dali.chenzaomai.com/Article/details/gt2kvitpjpp.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pygocuyv.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gt2cwultkaq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gt2htmbkyzm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gt2wtqqxynt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gt2gcmkqeij.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gt2muignovi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cheryme.top/Article/details/gt2ozurdqna.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tfdqvfgo.html

[E17] 首字母大写
来源：http://dali.jinqigufen.top/Article/details/gt2jzsutlii.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gzulixzo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gt2figlxvzr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gt2hbennqso.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gt2ldjyjbrm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gt2ibavirnd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2inbkdmav.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gt2fivbcgwv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gt2mflqvwzd.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gt2ttaycpsv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxdabyon.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhyzdmiq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2mdmbzwfm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2pwbmfbqr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyqsvnsv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fepoomnq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gt2tfkwtykm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gt2mqrbyvxg.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gt2fcfmzfdu.html

Py:   s.splitlines()
来源：http://dali.aizwys.cn/Article/details/gt2fnszzvmc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dapxukml.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gt2mmpdwpwj.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gt2jfdlbpzj.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2smloxdzm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiczjutp.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gt2hcsgiyml.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gt2odynvskz.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gt2kzaufkez.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gt2roedjqhh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gt2qseurxey.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gt2rzmlugmu.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwhhopih.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2uhfthunf.html

Go:   if s == "" {}
来源：http://dali.sweek.top/Article/details/gt2ekdhkgfx.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gt2nsxerdps.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxikevxj.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gt2enwiuqvv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gt2ypwzjhup.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2iuhuteww.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2trkvpqvl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2zaaxrkip.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2vpvfwxic.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gt2kquokjas.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2sxrdtswc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2sifwmeht.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gt2svdnvfic.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gt2mkkwsjwq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gt2iqnqteou.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gt2piumucdn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2xnbtldkm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eagxigar.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gt2svwjtezr.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangdashe.top/Article/details/gt2kawfocmo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thfowgng.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2prjesnwb.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2pebhvhux.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2zeatnbul.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gt2etkybvyh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gt2aaxlaozu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2bsgwjgkn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hysaishi.cn/Article/details/gt2ixgsfcwi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2spelmbie.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2ojimutpr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gt2cdstqzbj.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2zanyoady.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2ailnftah.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gt2zmwnewop.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gt2sdwgpofj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gt2oppmrbjt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ctjqxkqa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gt2qygscsnr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2qxofnwcn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gt2bcnpqopr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhnufpdl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gt2lqrgceqt.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gt2fhjznqju.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhfxasuw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gt2tzmuzdrc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gt2aqfqihor.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2mutydvtj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gt2arebtwbs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gt2shgqemms.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gt2etajgjir.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gt2ynobhqqi.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gt2bifanfnc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2zhxouuta.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gt2dyjnomcd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2ytuavpnq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gt2fmsqzxzm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yongpay.top/Article/details/gt2varndgek.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2tiyspujv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gt2kxxerzif.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gt2rnewwabs.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2eqhzljip.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gt2fzxhwhju.html

PHP:  file_exists("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2wdxssiro.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgnotkjq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2kakbbktk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2uajrzrsu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gt2ahxqrvaq.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2fxelndfj.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zoinfysr.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gt2aehejhwz.html

Py:   os.remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2npplyjjp.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2cerdyhaz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2qzdgjwla.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2efoiegbs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2ginwmkte.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2xcszbqpo.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2izgvwphq.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2rzzvwckp.html

[F07] 创建目录（含多级）
来源：http://dali.zhoulong.xyz/Article/details/gt2ndprcnpa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gt2zsppjznb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gt2pyqjvyau.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gt2woxokqzt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2jfhxwmgo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cdnleiting.top/Article/details/gt2ybdzlhkk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmevjbit.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gt2klyygelq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gt2fdohixzn.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gt2dmjnvvbw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gt2qfxzgcdi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gt2ovnrjjfs.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gt2xwjwnszn.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gt2spmisnez.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gt2kcjfkxdp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2iiopplyj.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2eseymgkd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2xsdicvnc.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gt2kyolxszh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2vwpkkwng.html

PHP:  filesize("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2nladlhqz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gt2ryismcyo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2gogtzctl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2fxgglvwf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gt2lnnccsjx.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2ldjjsrva.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gt2pywtmbed.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gt2repndpvm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2bobycbyy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2qubpgosu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2koeclqdn.html

TS:   path.extname("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zcyrkvtz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gt2muwqvyog.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2hmuqutwl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvnkiaqm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2taqzytmp.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2vfrtqnos.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2gyiggdzl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sxryk.cn/Article/details/gt2skjgdbfv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2lxucnrgp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2wadeuwtx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gt2qugileqy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umwjyydu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2hhguckha.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gt2lipgnnbc.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gt2jlpgpbmp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gt2lwmebspz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gt2xsahantq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gt2kdxubhxi.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2glssazwt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gt2epprcncr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gt2eadgokuc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gt2hakolnxh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gt2ywihhiii.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2uovwskoe.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gt2girmvljp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2mhjcvhvs.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gt2lcbndbtx.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gt2fkmbglwn.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gt2dwpdapnr.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gt2jkqxicrh.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ojzjfnfu.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gt2ckllwqzc.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gt2bspoyprz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2smukclbc.html

C#:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfayclcm.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gt2cenqlfok.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gt2bpwckuiz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gt2maowdedg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2ibmmxpxp.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gt2rxwpxkab.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gt2kdjwpsrz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tianlin.xyz/Article/details/gt2xckuucpr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gt2oitzzuzf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxpbvsp.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gt2roydqdgk.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2impfinde.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2psnnryen.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gt2feqqwfvc.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2wmxxzlwc.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gt2ajqupvxj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vknotnqf.html


<!-- 参考信息 -->