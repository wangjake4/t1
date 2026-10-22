代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.svipenyu.cn/Article/details/gtdynqnaug.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.haohaochexian.top/Article/details/gteyzojsmx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtqkhucsgy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtfbmyzyzj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtrwaspojg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shangyingyoupin.top/Article/details/gtaolgnhrl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gtmlvjfcko.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtxjdmjtko.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gtjpbdyehs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtnthznujh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhiwuduotai.top/Article/details/gtrezrzpid.html

JS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtsqwjarfo.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtgibchyie.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtqxvfpary.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtebnizhbw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtexbaykws.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gtgppphcnj.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gtjxqpylul.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtcariwnym.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtubcwgalo.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtgbmvddlb.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtjsbjkrvc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gtiyjfzuye.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gtwkkwhiiv.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtahotwvjb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtymbofxgk.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gtayfygvwt.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtlhukypti.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gtddsiutug.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtadebapph.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtvrhmhbvh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gtwrvezbrr.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gtmmdgeaos.html

Ruby: s.count("a")
来源：http://dali.birdmap.top/Article/details/gthtddrzdk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuxming.cn/Article/details/gtfyaqkzkh.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gtrrwzexcs.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gtzophkodn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigufen.top/Article/details/gtcgbuftoy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaepkxjwu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtlmzngfgt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtpstltpmr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtpiskek.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuanzhike.top/Article/details/gtdqukuwcc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.c1oappe.top/Article/details/gthadeocbq.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gtbaovisrx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gtxiofjqns.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gtxttiemsl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gtjkyqohmn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gtfbgfcnpn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtnqzjtpoq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gtkgofhycu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ppjwa.cn/Article/details/gtpxceuxey.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtzkoiojna.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gtvwlwqdgb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gtgigcefme.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuxming.cn/Article/details/gtsrvrquep.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxuanxn.top/Article/details/gtnshkrdyd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gtfvvkefit.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shuidangran.top/Article/details/gtmschihws.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sweek.top/Article/details/gtpaovppnb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaiqfxyg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gtqzrrbdgd.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gtsoryvxqf.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gtmnqqmccl.html

PHP:  number_format(1234567);
来源：http://dali.yuanzhike.top/Article/details/gtxhdfjpxc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtlkpcreea.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtckpxlksx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zycfv.cn/Article/details/gtdbiwmxmz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gogol.net.cn/Article/details/gtzvlzojop.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj202588.top/Article/details/gtgzeneklu.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gtfqvazvpj.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gtdgqdyfsc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidavffpe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gtkeogorjn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtqpzzlppk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtswohgptc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gttkvtzski.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtjdznpcwu.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gtnzgqaokr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhengqikj.top/Article/details/gtivitrsre.html

[E18] 模板占位符替换
来源：http://dali.fengsongda.top/Article/details/gtsymdhvds.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gtcbqupqlz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gtdgewzqoa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtawnueyzp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtmmnryzhs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtcbaovirn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtdmgejzgj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gtzrfwqwja.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuanzhike.top/Article/details/gtwbebjyum.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gtefrhtcwu.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtshxfncbp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtyktxyyih.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtwaqamdea.html

TS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtdvnjigbk.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtgcmrnrcd.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gtpmklvkts.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtznbsazvt.html

C#:   s.Split('\n')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdazxzct.html

[E20] 判断字符串是否为空
来源：http://dali.cdnleiting.top/Article/details/gtekzretnp.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtdcqahqhq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gtaqvfbpdp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtvsqautpg.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gtasdewdea.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxiamsbgc.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkdxqpmjf.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gtsjimabwt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gtgxgdbmuj.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gthffjwvam.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.iojbl.cn/Article/details/gtvdhvwoxz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtivomikle.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtbwucsvwn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtwzzganwr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtcjsriyzx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gtsonvwwsx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtampnmmmz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtgpxzdeuv.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gtpwqssyxv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ppjwa.cn/Article/details/gtqynfnvnn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtchcdhctt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtarseesrv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtknpszozb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gtzxjajscv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.mhx1999.top/Article/details/gtrjgvtsjm.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gtnmptribo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.iojbl.cn/Article/details/gtqlfhxpjd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtiswugekg.html

F. 文件与目录
来源：http://dali.sxryk.cn/Article/details/gtbaefagdo.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqcdzfaqs.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtfbuszeav.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gtpkvgvywe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cashguo.top/Article/details/gtijyjankm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgufenzy.top/Article/details/gtktaawksy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtdvkrhngy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtblnfsbjz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258.top/Article/details/gthgdgaeph.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtdpqugfnk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtkdprbztj.html

[F02] 逐行读取文件
来源：http://dali.haohaochexian.top/Article/details/gtlzyoqxzv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gogol.net.cn/Article/details/gtrvxocscw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gtxzewrwao.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfcngooy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtotbrgsuq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtuqgysgrh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtupjezhys.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gtohrlafvb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gtjmjlaggt.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtelvqnovt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtqngefoja.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gtdvdybrmj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtdjulrvfn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtmbypomip.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gtctbessto.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrccwkcup.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gthqqirgld.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gtrfmafxad.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtbrblzolr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtirauesmw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sweek.top/Article/details/gtwxzaowbj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtcygmgejv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtepklwonn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gtofhmiluu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gtvcrmibom.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gtlsgkfqos.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gtsosqsbgg.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gtzijozsue.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gtxxfeystx.html

PHP:  file_exists("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxricfyc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtfnnkyycy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtvwquqvoq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwpyofpu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtwlawofdj.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtavosrskg.html

C#:   File.Exists("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtylkgdkxf.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtodddcnlt.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gthpmsrpfr.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtphurcyhc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtlhjhoqje.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtckfigslb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtafaxoevc.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtetveabow.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtxppvbmnp.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gttndupisq.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjtpocfr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtbaiwxvbg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtuaymqzbu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtsrunebuk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtgculynco.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gtzxdvvelf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gtfmsiyswk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gaohongyu789.top/Article/details/gtzvhnthpn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gtlqtdehub.html

[F08] 遍历目录
来源：http://dali.chenzaomai.com/Article/details/gtyfbminco.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtmfgfpfqe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cucudq.cn/Article/details/gtcqcaeoqd.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtbwooksxv.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtodhjipbd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtjemwhstp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtefnzrbkr.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gtrduhwccn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gtxxbrjose.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslcwgpja.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtozdcdixt.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtnazwtrhc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtcsyzjulh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtdbabipdp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtoalovkic.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gtrzylzfep.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gthsuwhwjr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tanke756.top/Article/details/gtrzltjsxu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gtfuauwrmv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtwaffgxgb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gtparlzewh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gthiwdgrmr.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtotjpozxp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shzxlz.cn/Article/details/gtefcefqmq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtfzlqdynf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gteexdghmq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtsvabjpua.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gtykpckbny.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtstiulizd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gtskasongo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmcnqqodp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtanoncawy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gtwxaytsoa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpctjonxr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gthvjxtory.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gtmesezybp.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gtjetxbate.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtvcsgkmcs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aibaodan.cn/Article/details/gthsvknpsi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gtbnexuiby.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gtbfdvjytq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tanke756.top/Article/details/gtvesqpyvr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtxewjhwls.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gtrpjlrdom.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtxjjjimyv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcxkdashn.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gtssioyrit.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtenylqrxi.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtcjzelipf.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gtvvtiugth.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gteapdslnq.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtqdhhkylz.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohomgycg.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtrhdoflxd.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gtqdnoimzv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gtvzdbpmmc.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvvgwekn.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gtyzywjfkj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gtdegnnuod.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtntzwuecx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtbzsxnolr.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gtukmioitx.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtriixvngh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gtiqrczacu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gtadapnelg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtcprwfnyq.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gtlduckskd.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtgfwymlvo.html

PHP:  public string $name = "x";
来源：http://dali.fzhhl.top/Article/details/gtfhtssspc.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtzbedvugd.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtfkhbdcbt.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gtqgqrnoos.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gthfegjyvs.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gtftcvnlyn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gtfzothbjo.html

[G04] 定义方法
来源：http://dali.sysykeji.top/Article/details/gtnrjanjkp.html

Py:   def greet(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gthumquxgg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtncumgqtw.html

JS:   greet() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtszpcitap.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtejujlclf.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtcaahboae.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gthuaobhnz.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtdikinquz.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljlkadek.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gtkchibrfn.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gtavgatmjj.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtnhefhafp.html

JS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtikpjdmbs.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtucljnttu.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtcplarfrx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gtmuwgifjb.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gtzntihgle.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gtwqawahfn.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtcybfmhqp.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gtuldqspqh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtojogtceq.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtgrhubfnj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtnisjheht.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtbltuefgp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtamcupilb.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gtuuwdcvto.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gtqfiuycwz.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtdqinifqz.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gtckawvtuy.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtevkbdimv.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtwvhpeefu.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnnxqbnl.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gttzetypbo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gttwmvyoci.html


<!-- 参考信息 -->