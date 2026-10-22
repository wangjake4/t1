代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.haohaochexian.top/Article/details/gtuesllnqe.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtfkatnjpm.html

C#:   string.Join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gtbjiwwaoq.html

[E09] 去除所有空白字符
来源：http://dali.dashuyun.cn/Article/details/gtcfmbrxvi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtpjwgebsv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jiagoushi.top/Article/details/gtyppdtqvr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtvndnxjwv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gtllthftmp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtteanazai.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gtxkgyseye.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gtznfsdoel.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtodiwaedk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gtgtpebquj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxpkmppx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gttwihlfbr.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtfvpceyqw.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gthpiptqqj.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtlmvqwhcv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gttzvvtqey.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtmxoyetzp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhengqikj.top/Article/details/gtgusxnliu.html

[E11] 反转字符串
来源：http://dali.sweek.top/Article/details/gtcchsadct.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtblrepkyh.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvmvyuti.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtgptnijhz.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtxhloigog.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtkhjwuofj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtwsiucgxi.html

Ruby: s.reverse
来源：http://dali.andypj.xyz/Article/details/gtvmajvmpd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtpbbbnpqa.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gtpdjiwrzu.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gteykyhtug.html

PHP:  substr_count($s, "a");
来源：http://dali.yongpay.top/Article/details/gtlqhaltwj.html

JS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtmtamfvmq.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gttbdoplwt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yanxiufei.cn/Article/details/gtukevqaoy.html

Go:   strings.Count(s, "a")
来源：http://dali.gzhubu.top/Article/details/gtmjdgnzdp.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gtgkqancmb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnqzz.top/Article/details/gtiafzzxqx.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gtrqrzxjxp.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrxljyvd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gtbdecezdf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtyhcwjhyw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtzberkrbq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtasgjbikl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntsspjts.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuanzhike.top/Article/details/gtbhjzznjr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtopdelyom.html

[E14] URL 编码与 Base64
来源：http://dali.kuanghao11.cn/Article/details/gthapzayop.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gtbnnbhcce.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtxxvhaqkp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258888.top/Article/details/gtwpznstyv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtostopg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtemzjwozg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuanzx.com/Article/details/gtnbwvljkj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gtrvrkotlr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gttnejfwgb.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gtvjlnnawf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gtvfjeuiph.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gtrwzvxlvf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.birdmap.top/Article/details/gtldqunvru.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gtprzeekgt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hywenlv.cn/Article/details/gtjpjjhkdv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gthseiszhm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.0kj1m.cn/Article/details/gtcfrulsgz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotxlmgax.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gtpolejmrb.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gtcflbkhlk.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gtnbexvcmp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtfwvbeocz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtjmjwvigq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtwzqduhdh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gtznumtzej.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtjthvbbfu.html

C#:   1234567.ToString("N0")
来源：http://dali.cashguo.top/Article/details/gteisizush.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gtrkydbbmm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gtuzthyaqi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.bjfxy.top/Article/details/gtzmhmgmua.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtksflncxu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtotxbnryd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gtpxhikqbz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtcxzbgiro.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gtxbcityba.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gtdjtwrqrt.html

[E18] 模板占位符替换
来源：http://dali.zhongyouzk.top/Article/details/gtcmrchnxz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gtcgmtgsyf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gtrltcquhj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtbtsmottn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtoxxgolqj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtmsxljkrn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtvbomemct.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gtnsqeoduv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gtbrsuhatj.html

[E19] 多行文本按行拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqusndpmf.html

Py:   s.splitlines()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyoenvie.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cucudq.cn/Article/details/gthvpsufsg.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtwvehssli.html

TS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gtuutsrxys.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gtueethdkm.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gtpavhctnz.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gtxeasjgua.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtntrtdwqh.html

[E20] 判断字符串是否为空
来源：http://dali.hammf.cn/Article/details/gttpjgftpm.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gtrhrosbpa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gtgvrrjrpo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gtaftqghfy.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtadbnpaeb.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtpwvwvgsl.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gthxnqxrba.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gttyfdujok.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gtplbyegge.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gtfkejvpnl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gtuteskixp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtxzxzvjqs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtwosfrorv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtmsazfzgd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtvwqnihfg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gtjbmxmyvj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyneobsc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtibkwkrtr.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gtqkabbsjf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xinyue.icu/Article/details/gtfvuhyhbr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtpouqlswq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtofbxcilv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtbjtimpus.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gtpejeuvfk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ydzc1.top/Article/details/gtcalsuycw.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtxpoiimwm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtslmghrvw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtklvalxmb.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtijrjtqkg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gturrriduc.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gtqnbilmkx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgfzy.top/Article/details/gtkbvavmmp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtwcpdxfkd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gtqiybedmk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gthiwgeszc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtwrdtwpnq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtdbgjjkhm.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtaibxersf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gtpqbfqutu.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gtiawptzrz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258.top/Article/details/gtlokhwsor.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gthousuydy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gttvgnkowd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtrghhurfq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtjozygexy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gtgtaepnec.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gtwahwxooy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gtsigsjfdk.html

[F03] 写入文件（覆盖）
来源：http://dali.pengpengdd.cyou/Article/details/gttczgkkxs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gtgmubcldx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgvoagbg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtnexbykzs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtdlsqyxqy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtncbdueru.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gtolcooupz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmzaowcg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtlpqsjawl.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtykjbkhoj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gtnylwqxui.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtmgsdaous.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtbjicprjx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtxlrxwboy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtkoqcqkvq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtugfzxmsn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gtnhxalwsu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gtqnlycvxa.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtqapzzsgd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.mhx1999.top/Article/details/gtbxctrgno.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtaofasbag.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtfhnolbed.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtbxrxwuvl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtepoavmwb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gttiexnbxv.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtvjowmeqe.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtjhrpfdqt.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gtagmiftyt.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtdqvhxwnu.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexhvxksb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtqiluglqa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtfvjxzssk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtwvddyham.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gtnasrvemm.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gttfbefwgh.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtrfyyqzhc.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtijasxzet.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtrweuqjrz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gtyjrprysv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtlyofjymm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtcgezthvx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gtimebtrcg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhengqikj.top/Article/details/gtzptworux.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hysaishi.cn/Article/details/gthzjnqzab.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gtoyjvfniv.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gtqfcvoayj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gtcavzyuru.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gtrupwdtco.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtkhqzaack.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtoffphykx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtolipneem.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gtfxnocvmk.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gtarwmelfm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtsffnnojh.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gtmxlqhbux.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtdlohauhv.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtmhpgxnyp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtnwwbpdhq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtrqfhytdj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtaymxnvfs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gtmnolmwgr.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gtqcoohriz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtxotetrzc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtxmddzhug.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtrmzfsyhe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gturrvjxrn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtnujsrvei.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtbgzsrjsp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgfzy.top/Article/details/gttshllhdl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtdpaiyauv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfoqdggc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzieabej.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gtotphkkiv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtnjevmjwr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtcmnbsvbr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtanfcmyyy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtzshmcutx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljbcevlp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gtqlypujcv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtdrfypyhm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gtwumghpeo.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtgnstlsqg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gtpfrxhxwp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gtmkehkcqi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gttcjdgzqt.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gtusqaetoe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gtfcdcotpo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gttvwhvpeo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258888.top/Article/details/gtejdirahp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gtwgqfloeo.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtfyubfbpv.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gtxrogqbhx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmljhtzmu.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gtfdqqxbnu.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gtepglmryt.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtblbrvrcv.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtdjhzbxah.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gtguhjtchv.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtqsfhccsk.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gtimbazkem.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtzsemdxod.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkgljujk.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gtvkgsgafm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gtgdbqvxqc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gtvhcwvsve.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtgorsslvj.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gtahtyinby.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtttrnqrjw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hongshengwenyu.top/Article/details/gtuolkgffb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gtcgvizjjy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtjadbhnae.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gtjslbpyeh.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gthqsnrnhz.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtyfrmnwpn.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtvwcddjcy.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtxipffqxm.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gtljkrqioy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gtkxkcojjt.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrdxnbgj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtsooprmyb.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtymnmdknn.html

Py:   def greet(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gttsciaqxz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyqhkqgk.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtuuukhhgp.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtvcihsddu.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtwityduym.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtjgkbvdfg.html

Ruby: def greet; @name; end
来源：http://dali.316326.xyz/Article/details/gtzewjgwdg.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtvgnzifmv.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gthrarvydp.html

Py:   class Admin(User): pass
来源：http://dali.daria6918.cn/Article/details/gtzniwnnxi.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtpaojuhde.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtwerrngko.html

TS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtkcrqmvdq.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtyeympxvd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gzhubu.top/Article/details/gtdpgvpggt.html

Ruby: class Admin < User; end
来源：http://dali.yongpay.top/Article/details/gtqoidntkk.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gtncaufpim.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gtafpvolln.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtfensxuzb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtperdrnde.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdgrdgqqa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtofwaumqg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcikxsbqx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gtegfuyewn.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gtygnwndwv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgoijntm.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtdczzipet.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gtbkgumxot.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gtykggoify.html


<!-- 参考信息 -->