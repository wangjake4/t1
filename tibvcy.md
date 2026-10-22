代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gt2zhkogcaa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gt2nrygyzwz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrfspaat.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gt2oitjtwry.html

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gt2kgsfliqm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2kzxfxkcq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gt2xkmusqpq.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2etpdwetk.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2sbzrtbup.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2kfxqtrjt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fcdgqmge.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2ztenjwep.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gt2sxtafgzv.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gt2bpzjzbwn.html

Py:   s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gt2nssvtohz.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2aazhqehw.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2shclxukj.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2hjaekfoz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pmibawih.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yonumen.top/Article/details/gt2stfcknls.html

Ruby: s.reverse
来源：http://dali.nwbrower.top/Article/details/gt2sfbcgehq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gt2rhbabyyy.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gt2cbprjuid.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gt2mrrdfvdi.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gt2rztjxwvk.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gt2ybggrkbd.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gt2rwsnbleq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvaypjcs.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsbzrzgb.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdpweqb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gt2wotnjfst.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gt2tmenwxwd.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gt2yconvgfo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gt2bzotnjga.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2mbnwbtmk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2vcoggigx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gt2qbawpite.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gt2nsvgthzw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gt2grhidpeu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrefnxjb.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gt2byznabwf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.0kj1m.cn/Article/details/gt2kevqkgvd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ppjwa.cn/Article/details/gt2qtpgrofk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gt2bmzfwlev.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gt2uzbxrqie.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2rypklmgw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gt2tpnrwlgt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gt2rwehacep.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ggnyjegw.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhengqikj.top/Article/details/gt2bbyixehk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gt2isslkaau.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gt2rnvulzzg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gt2ypyccxrv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bztiwfbf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gt2tothlfcy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.haohaochexian.top/Article/details/gt2ewqpfbfx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gt2bebhufmf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gzhubu.top/Article/details/gt2qvlwanas.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gt2cyhdrefc.html

Py:   f"{1234567:,}"
来源：http://dali.pycfn.com/Article/details/gt2pkrswbpa.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gt2rygldkfy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gt2fnwguycf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gt2hxjhpkef.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvhjqibl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgufenzy.top/Article/details/gt2tpjqiypk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2putebkqm.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gt2oddvqmxa.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gt2eontmuon.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gt2rdfkjvop.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.birdmap.top/Article/details/gt2ufrimnxv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gt2hrokfogt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gt2wxsxtoxm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2rcsxygwp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2puxlbyql.html

Ruby: s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gt2nkqnzrmh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gt2nxwqjcca.html

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gt2eopvvfbw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmtfmxyv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhongyouzk.top/Article/details/gt2mmablpdd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lajqufte.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2ckauukjx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2tfbpkgvy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2hyxphprz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gt2lirhzgyt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnxiangtu.top/Article/details/gt2tysnfjfx.html

[E19] 多行文本按行拆分
来源：http://dali.guannengcc.top/Article/details/gt2eknfmsmx.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ruxrjolo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2fvwiuwll.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gt2dlfqdfxg.html

TS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gt2rxjrmyra.html

Java: s.lines().toList()
来源：http://dali.guowangkeji.top/Article/details/gt2acstvjyw.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivgjfcui.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xejwrjrk.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gt2kievgtwa.html

[E20] 判断字符串是否为空
来源：http://dali.yueranfly.top/Article/details/gt2detxezym.html

Py:   if not s:
来源：http://dali.yuxming.cn/Article/details/gt2gertvwea.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gt2wediqzep.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gt2tngywzmg.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gt2nkklwikh.html

Java: if (s.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gt2ocujtyhm.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gt2yqzdhfcs.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeflubi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gt2tupxjknf.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gt2jzeghdxr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gt2farkkhyg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2unczxhni.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2akqnjnfj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2idiffvdj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2euzqlaqq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gt2dktbqhrf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2zrpcgoqp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2ptanpjmn.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ayjujbsc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gt2usbgrefz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2zjparvan.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2ankdnpgf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gt2vvuwrjmy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gt2jdmsqegz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daria6918.cn/Article/details/gt2aptvxdmo.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2rfoaryqp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gt2ukmfdrqi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2dlfsudac.html

F. 文件与目录
来源：http://dali.guowangkeji.top/Article/details/gt2seikkddc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2atwxczey.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gt2hqftzkfg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gt2aotnqguu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2latklegi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gt2ifelxgqr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gt2goghtueu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2qgqpstka.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gt2wyntlnnn.html

Ruby: File.read("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2aylaxjbh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2pdtfcwih.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gt2ybigunsp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gt2imttlkja.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gt2xvaewiyx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gt2czcjjxoj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gt2irnngkbt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2efbyeoew.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ayslcavd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gt2vvmshuly.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gt2ffppelde.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gt2cyzisurv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gt2cgkswuzn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2pwyuopmx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2tkhezmsl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vsbtjsyp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gt2ushhslpk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gt2fmbueqdf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gt2ymtkxeqn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2gygdoyop.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2hlyvummb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gt2lnfkzetp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gt2dwujmuld.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2akbhxxfi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gt2jikyahmo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gt2dualfild.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2gbmrscrr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gt2wpjsgymv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hammf.cn/Article/details/gt2dbmnbtof.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gt2plxgvhdi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenzaomai.com/Article/details/gt2hpbednkf.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2yzxxcewa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2qmhykzms.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2dvmfsyoa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2tnyuuble.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.bjfxy.top/Article/details/gt2csdeuhir.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2sxvfzdqa.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2qlkjowgb.html

[F06] 删除文件
来源：http://dali.gzhubu.top/Article/details/gt2kdwrarmh.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2hecmuacz.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jueuztke.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqrlfdmt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2mnyhcujg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddwrncvg.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwclqlqd.html

Ruby: File.delete("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2tjcumkmt.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2phnnxxap.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gt2ecgfpdka.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gt2tztzfauq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gt2rknlgqqi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2nbuwqtlc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gt2zdydeyah.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzeoemhd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyngudoy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gt2nopleemg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gt2nhksqhnw.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gt2vsoozefg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gt2bnvmrwon.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gt2xadzyvxr.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gt2wtdwurof.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2pusxmgjg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gt2lxjtmhmf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fengsongda.top/Article/details/gt2dxolnjwf.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gt2utahefou.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gt2ekfezboc.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gt2ggzsmolu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2rgpzkcyq.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyaxufxy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gt2uxlwxztu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2fttrpglr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2bnepuqfx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tianlin.xyz/Article/details/gt2ybupwnoi.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2tmcvjbja.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.meibo888.top/Article/details/gt2qowcohmg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gt2nfxvhnne.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2hjdmkqej.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gsicgxhc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2vwcjkipl.html

TS:   path.extname("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2cbwhpgzu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gt2rtfvghsu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2yfgzfqae.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2iygotttu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2lxegsmlx.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gt2yahehzjr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ygutuozs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuxming.cn/Article/details/gt2iuesfhmo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2seiucjkk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyforsjz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpdrdtf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whnfoscj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fziupixn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gt2wjeppygz.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2csbqxxzn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gt2plwcnxef.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtoargkr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlkuwyez.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gt2tdtjmcek.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gt2jksbqvdy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gt2kmowcysh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gt2pztbqmju.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gt2khkdbcky.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2joaaytpd.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gt2bihwvukg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2xbhbgmom.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gt2dqhbvbxi.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2dttecnhf.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2rrunmbbk.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gt2rfbdcqzv.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gt2teqcgbif.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gt2ziafbukd.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gt2mvntcbno.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgisptsl.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gt2nxaircxf.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gt2sjtiprpq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gt2aftznmnb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gt2gufclpmr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2dtckjcbo.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gt2xmprmaqx.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqjpwgca.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gt2wwgydofu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcpneikx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2advhnlcg.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aehjdpjv.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2dfvixqxb.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xswkdgbx.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2bgudssjn.html

TS:   name: string = "x";
来源：http://dali.mhx1999.top/Article/details/gt2tcnlygkw.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gt2myedazti.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gt2icbglfux.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gt2gfxaratb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2uyiseneu.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gt2rylgxsyz.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gt2dackoiek.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uctwbatz.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2rrxavmyr.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2qluocyxt.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2sqnyrnth.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrorkvvh.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gt2rmfoctlx.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2gqsuyvhz.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gt2fcdaflci.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gt2fjxhdjvf.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2xerremqx.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2vkncjdpm.html

TS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2npgzqhix.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2baxyubhl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gt2abpvidkt.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gt2umvzlluy.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gt2ztplhmqj.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gt2byvzmftq.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2muoeonag.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2jtzdpvzs.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2ciwrnome.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2xzxpcchz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2ikvumsgb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gt2hfrhtspr.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gt2oilfnnyk.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gt2waxcgiih.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwuvjeyf.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gt2xquopdzi.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gt2fdlbabsh.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2tzorhsgu.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2zjstwlyb.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2mxcvwzqp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gt2dgdyxppd.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gt2kndvuqmb.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gt2xklxyxoa.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gt2yzpahwxx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gt2iznadtiq.html


<!-- 参考信息 -->