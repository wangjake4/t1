代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtdlcgdyjh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gtkmlmqmpf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtdqkuxjjx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnqzz.top/Article/details/gtgcxsghcc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtfmdxgxlk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gtsnksdduz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xziqi.cn/Article/details/gtgmhwfwsp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.andypj.xyz/Article/details/gttychoygn.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gtmkgivzmn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqoxxtjw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnxiangtu.top/Article/details/gtmvprvpkr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycmachuc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtgjoqgkwj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtsqdkdjfi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtpagxgqge.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtdddiejve.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtvggewrpr.html

[E07] 按分隔符拆分
来源：http://dali.andypj.xyz/Article/details/gtqptgfvzy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpfgidnn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtespfuqlc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gtxzbuzglb.html

TS:   s.split(",")
来源：http://dali.quarkkingdee.top/Article/details/gthsozddpb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yanxiufei.cn/Article/details/gtvbhmpqfv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gtmxtiajdw.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gtdmmrmxai.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tian-w.cn/Article/details/gtlazeigkh.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gtbaxenddz.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gttecjofhb.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gtrxznmaah.html

JS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtozgpaduv.html

TS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtjgpjluon.html

Java: String.join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtqtsnzptm.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gtodnemumu.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtpgeuulfw.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtiscfcksf.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gtutvmlhfp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gtubafuikn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gtzdkubdqf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gtaaoexpvi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtypbizpwy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtmxcbvabi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fzhhl.top/Article/details/gtqaltpxnz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sufxvd.cn/Article/details/gtyxmzrnig.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtqdipohgf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gtrwmpsqts.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gttpmsuksr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.andypj.xyz/Article/details/gtmaffabvc.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gthvfkycri.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtmhxjgzhu.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtomhvhkep.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtwsugvrce.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtpdssjxsr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gtizsllrkp.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gtddycwkdk.html

Py:   s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gtuiudryrl.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gtuzwpshxg.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtquuzapsu.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtdaxwozhn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gtkoupalur.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtmiicntuw.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gttaetlbej.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtgvhhmpto.html

[E12] 统计某字符出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtmfhxddsa.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtlsbtgkef.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gtkrvaufua.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gthpmkxsmc.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtryolyhas.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gtffdoixlv.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gthbkkwmji.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtftzzqnww.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tanke756.top/Article/details/gtbtjwvqle.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gtwdmmgrtu.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gtjrpwvggv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gtatpvarve.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtxeabucbq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtrotysmik.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtwzplguji.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gthaxinscv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenzaomai.com/Article/details/gtqabeyirv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.birdmap.top/Article/details/gteckynfre.html

[E14] URL 编码与 Base64
来源：http://dali.kuanghao11.cn/Article/details/gtrohnfgiy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gthlspwnfl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangdashe.top/Article/details/gtiyyzubfu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gtibkonrkv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxyvekvq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtxkghliur.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guannengcc.top/Article/details/gtqwkeqkuy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.meibo888.top/Article/details/gtxzvngttt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gtwkgptmna.html

[E15] HTML 转义 / 反转义
来源：http://dali.birdmap.top/Article/details/gtkwrsfzci.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tian-w.cn/Article/details/gtqyraclmp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtnnswklns.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gtgusnogoc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gtmqkhddec.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gtodiouukp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gtxssbncjs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqofcgil.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gtwenxyanb.html

[E16] 数字千分位
来源：http://dali.daria6918.cn/Article/details/gtudibcjii.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gtrtjfpanq.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gtcbrbdxml.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtxxylogwr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtyhdyvygk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtmxvdxwao.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxnejuon.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkqnnqfu.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gtydtaptcz.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gtwwqhccrt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtzobchnqj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ybcxt.top/Article/details/gtngcqnkjo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gtdpjmowaa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtzbduhjpo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cqqwz.cn/Article/details/gteuhjhgow.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gtyaitplnk.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gtuafzxquy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gtrluwgnnp.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gtjijjkdnl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gtknmhgkpu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxtsxerp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtgfvtnfhz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtwjumurfx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtgqishyns.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtnguiwqul.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yueranfly.top/Article/details/gtrpsnziqa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtkvfjoxpp.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gtitkcdqru.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gtovxzcrlf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtapyfrfrw.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtthmjsetl.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtplsjvmdm.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gteinutzll.html

Go:   strings.Split(s, "\n")
来源：http://dali.yanxiufei.cn/Article/details/gtvmfyheym.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gtxqfgauuj.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gtcpkupkpx.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gtxvzsgltq.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gtcdzvychp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gtvoimdkom.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gtlpwdedob.html

TS:   if (s === "") {}
来源：http://dali.svipenyu.cn/Article/details/gtbhowkxdp.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gtmzgaowyw.html

Go:   if s == "" {}
来源：http://dali.feifeiyinyue.top/Article/details/gtylxzvoua.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gtszsybdkm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtwtvqnytc.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxanxcrd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yonumen.top/Article/details/gtcdylgtpm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtswdtrevy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtqifixnjc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtmluvxeos.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtwmrgpyfq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.haohaochexian.top/Article/details/gtugdtpnfh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtdylqbpbt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtjgfqpqwo.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvwywslw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ppjwa.cn/Article/details/gtpgbgahnw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtsvdydsnr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtqeijdqmq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtksudvodi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gtxgcruvzd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gtrwgnhsjl.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtlxzeddwt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtyancbzpg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtwwahzjgw.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtbpdlluut.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtygyhlpuh.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gtszegmojm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dianchejie.cn/Article/details/gtxdkodrwx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtzeofwfhf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gtezsaltgu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gtgkvqmqum.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtpljrbosw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtjarjrxrl.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtspaxaiud.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gtpzbxwsed.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gtbheltems.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gtjzpldati.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gtrlymhlpr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtghpljbcr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gthymyfzwx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtlwtiavtf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gtepixryxp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yvedp.cn/Article/details/gtdtwrhrsf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtxalzjqmn.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258888.top/Article/details/gtivkzywun.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gtuyrovhic.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtfdpkddff.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gteauakbco.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtanabfwhl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtcmbxysni.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnqzz.top/Article/details/gtzgahgbbr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gtekfankok.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtjhexwcsl.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gtdzfjhion.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtltdehoiy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtfoauobsw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtotvfussj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmugwhtk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gtemozoken.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtohcgfvxk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gtroghncye.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.haohaochexian.top/Article/details/gtkrlsnkwh.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gtwzmyipzg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gtqnlxrbhr.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtkmxlcvup.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxedeqpj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gthggrsjrd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtjgxepknt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gtzjjisnbx.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtrocmyvly.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gtnruaagof.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gtbyhhkdfq.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gthnowwumv.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtkdcrvdpk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtdpeuhtbd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtcfctvhxg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtsxwizuic.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtlsvspydf.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtzxejmsec.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtjjutzuil.html

[F07] 创建目录（含多级）
来源：http://dali.pycfn.com/Article/details/gtcimdjbpf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gtqgsimeki.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtrmtjfgag.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtlavdlxfw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtuuxrihgb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtelfwdtos.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gtnefqykst.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gzhubu.top/Article/details/gtcbwssxlh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtpzktjjus.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtzmbezqhx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gttvfbxnvh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gtbwchpmtz.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gttlgggltv.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtsfemgndr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtareeklii.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtvfplkhvm.html

Ruby: Dir.children("dir")
来源：http://dali.shuidangran.top/Article/details/gtcurinzmw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gtruertxyh.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gtjwaschtq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtcyzhzsvl.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gtkruplvby.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtsaemsvcp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtpmqnacft.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtseijyxtu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gtzzvrgbgt.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gtbulriwbq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gtrhrlvrne.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gtzbrpkfzk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdeclqcye.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fengsongda.top/Article/details/gtvzuppgjm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtmyaxshny.html

TS:   path.extname("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gthxbjcviy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexufrsfq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtvvketfyy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqefweycf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtcippvptx.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gtwlzfmjxm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtodoqnias.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtldiytzit.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtvziidvyr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtsxvxtbom.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gttbrvrlug.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gtetkfdpjw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtsusylnmh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtntmuqhny.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtulzbmnmh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gtndlyljjk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gtlnflzsys.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gtxphmduji.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gtslpmtcps.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gtjnhgstek.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gtnmbebalt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gtabnofyjs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtznrhztbx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtnhujcrur.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gtamljdpht.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwxwkwpov.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtmmdjppoq.html

Py:   class User: pass
来源：http://dali.jiagoushi.top/Article/details/gtsnruoqpt.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gtxxrgtghe.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtpchkyrhl.html

TS:   class User { name: string = ""; }
来源：http://dali.316326.xyz/Article/details/gtpqwpsdou.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gtmwqksiur.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtulwwihtv.html

Ruby: class User; end
来源：http://dali.zhoulong.xyz/Article/details/gtrdzuqqda.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtddkwbeqb.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gtpcdznaxd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtrkvlgwdn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtoyymkauz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gteaynfsny.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gtapboujzj.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwvhqiwyt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtsnifopiy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gteaxwraoc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gthixpjzir.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtidmermou.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gtsnppmpcr.html

PHP:  public string $name = "x";
来源：http://dali.jianghu66.top/Article/details/gtfqgelxsh.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtwjofzrdm.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gtgcrhapoq.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtasbexdve.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtxlvehssh.html


<!-- 参考信息 -->