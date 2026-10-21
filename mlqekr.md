代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.vqdsnc.cn/Article/details/gtryqwzsxo.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gtmwfgkxrh.html

Py:   s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtqzyltkqa.html

PHP:  strrev($s);
来源：http://dali.yj20258.top/Article/details/gtfcncksme.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gttzrbagur.html

TS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtdxfebwfm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gtjbjsgvdx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtrqrvoppf.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtzrnxrjto.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtthygzyxy.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gtkilzdyyg.html

Py:   s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gtgzyktvky.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gtrmltpaez.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gtvlkbblor.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtxysgniqj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daxiang520.top/Article/details/gtiubzrkic.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gtyfxbrzro.html

Ruby: s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtyhxhhmyr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zycfv.cn/Article/details/gtpjzvzshq.html

[E13] 逐字符遍历
来源：http://dali.birdmap.top/Article/details/gtbhquozbx.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gtumjcvpnb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zdqjudy.top/Article/details/gtgjeahdzd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjxuejgoy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtpdfrtswx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhengqikj.top/Article/details/gthpihoaou.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gtdyreszje.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ybcxt.top/Article/details/gtzpcxzatx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tanke756.top/Article/details/gtpsrvrxjr.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcyxhbqv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zycfv.cn/Article/details/gtlxkntwgn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aizwys.cn/Article/details/gtlmczdauv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gtjvamqfos.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.316326.xyz/Article/details/gttmlsrubn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjasseyd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gtbhvjmshz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgovchrr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtzchappdf.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gtvcfauohx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gtmqusfoug.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gtftnaimsm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xinyue.icu/Article/details/gtwhwkamep.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gtwnxhrrpk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gtaiinrvzb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gtkschnkhs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gtssmeeyne.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gtojwpfvpy.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gtckhewrzd.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gtgdqoihfj.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gtwgnttpmg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtuwtxewft.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteeomknnk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtsouauaer.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gtqrvfewgt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gtzdaxswvm.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gtslipoyrh.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gtofdwhugo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gtzlrejmvb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shuidangran.top/Article/details/gtcuoengge.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtmwxsdnmg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtloqoaqqz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gtpsclvkwc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gteuebzklx.html

Ruby: s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gtpzvagjdw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gthghaqetw.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gtwjoatanu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gtbzcllgut.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gthfxtsbmx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtcsffzyyh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gttvodjape.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gttbqxbsai.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtxkrthaem.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtevpskbjt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gtqkqceymx.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gtbfvfejam.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gtrxayetml.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xinyue.icu/Article/details/gtscoyhjgh.html

JS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtqaeoopjx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gtfnpktagc.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsuqrfcl.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhoulong.xyz/Article/details/gtwaawdmor.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gtgksegyqp.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gtczupsqmx.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gtddchyzrq.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gtnpnblqwg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gtdloofpbl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtuwdoowlp.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjjwbfqra.html

Java: if (s.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gtqtvyvjfb.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtlegouyoq.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtjpnqgtjr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gttoqlalgl.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghctfcje.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gtkdcuxpbb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtigfenezk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdetdzpd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtklonptrn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphdvcblb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gtxeddwohw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtojfdzuon.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtuezpribo.html

[E22] 字节长度与字符长度
来源：http://dali.jiagoushi.top/Article/details/gtlqdskewo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gtjmirkspe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtvgwdnshu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gttwqldixc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtwwktfaoy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtkafywdcf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gtlmxfarcs.html

Ruby: s.bytesize;  s.length
来源：http://dali.daxiang520.top/Article/details/gtvrvoxhlt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gtzwlnriml.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtskrizwxu.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gtmomplcnk.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtybwbuswn.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gtjmavhkgq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gthsaauczn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtscjcojxa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gtqabpooee.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtuugszsfy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtegirxtcz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gttgloybba.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvflelrlw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtqrpngaef.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gtyemmnadu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gtjprgvuqq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gtvtzjikly.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtijazfmiy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtixaluthh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gtcjbbmizl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gttvmsczqd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gtfvbawhkz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gtlnugjkjt.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gtnmkjxvty.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihwjeelj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtiogsmlxt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gttfnwlulp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtwodxtclj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gtdzesbzkw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gtgezfgxca.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtitzwcgub.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtuuinvhbm.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtcujhyevd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtireghhax.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gtqalkqxvb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gtsbfghvaa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtntkbjuno.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gtmmxaytlq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtkarigxja.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gtxkjwntsz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.haohaochexian.top/Article/details/gtgsydjeki.html

[F05] 判断文件或目录是否存在
来源：http://dali.pycfn.com/Article/details/gtqpztviis.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gttpcgewol.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtevtusgfc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvwdfdgut.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtiojbulsn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtbxhiibtn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gtvfpaohtq.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtrwhvckxg.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtvherfzvg.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gtqiofgnxj.html

Py:   os.remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtdsyzacar.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbuneapeo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtlimolkug.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtkbcblvqh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtxzgjhjel.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdibhoaqr.html

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtxjjkgkuu.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfykoyut.html

[F07] 创建目录（含多级）
来源：http://dali.ydzc1.top/Article/details/gtwsxlpjut.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekiavjlm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtzgkbzork.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gtnbbgbxoz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtwqqpfxih.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuxming.cn/Article/details/gtulegumzm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gtsddnziex.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gtlhtwaenb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtlrperpce.html

[F08] 遍历目录
来源：http://dali.yuanzhike.top/Article/details/gtgfupppfg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtyzoypdyu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hongshengwenyu.top/Article/details/gtviwdkdrx.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtiujgpjkk.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtawbwfwtm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtxgklhpun.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtbbwtlwuq.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtpksxgjll.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gtnnnvdzsu.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gtlciiuztp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtmwwpkogi.html

PHP:  filesize("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtdnkmtryg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gtolpeqkhv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtnozijfey.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtwsymcdmq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gtjhazqndl.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtxclavsyb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gtgpufmufr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gtdcfryzxu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtshpumult.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtpjtrapty.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtmkvczeki.html

TS:   path.extname("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtnxqjjbhn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gtpmrajjxr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtuzvdkkxf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtltmmoaft.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtwqxpxedh.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gtenrctsdh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtlsvtfykx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gtslsgldqn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtditnmfry.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtpywygvvu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtccnuicrk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdryxadvx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtunxadwvi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cdnleiting.top/Article/details/gtqdkryrqd.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtfyqcbxth.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gtmgzrvjpn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gtevmngtvh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gttbvmkddf.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtsbhodifn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gtvpuryhrc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pengpengdd.cyou/Article/details/gtjzzshgzo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jyoumei.cn/Article/details/gtnsnwcbaz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gtmwyuxnvq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrbrdldkx.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gtilghimjs.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtehlkteku.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtcjpvfunp.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpzquijv.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gtoltdouai.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtsvhljcab.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gttgcahysc.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtutsggian.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gtrpqakbsh.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gtqcgylvla.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gtyjnhzhna.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzoezefo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwlelqyd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gtwntotxxc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtkdwggfjf.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gtozhnjpaw.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtuknggneu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.meibo888.top/Article/details/gtajqajhww.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gtivtgdbaz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gtpiqrwjhr.html

[G03] 实例属性
来源：http://dali.cucudq.cn/Article/details/gtdkpkdobg.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtasytodrb.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtmttiquuj.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gtyqmqctdh.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtfofqjsoi.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtyckrjmso.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gthhtiazrb.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtqdiinajj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtienbfdog.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtyrbrspns.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtbpsbqwlf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqxxytye.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtoiudehvs.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtsukfsuzw.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtclmacezh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtmulqakvv.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxchswet.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtsfmbvbgl.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtdrudivox.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gtowpzagsb.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtspcinquq.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbzdevnd.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gthgxzyqpk.html

Java: class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtbbopcyba.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcoqwxlix.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gttdivsnrk.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gtdkerbvyc.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gtkobvltlz.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gthnevwuuh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtnwcbxqvv.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtzspmsukq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtvuqzgkfa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtprmovldq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gtqntwkjhi.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gtrsnddqbk.html

C#:   public override string Greet() => "admin";
来源：http://dali.9152youxi.cn/Article/details/gtcvmijmli.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtyalijfnr.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzqrewgk.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtlaguvjwp.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gteahvllph.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtjsiiavub.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtrqiswlyh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtrelexkxl.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gtefzjbqxo.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gtoarelols.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gtnjfffiuf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtladjoqwg.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaflrrdwl.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gtcrusceid.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gtgfkrzpvn.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gtxfhurxcv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gttloldhzo.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtizazkuxz.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gtgubthdev.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gtmbxkjpxv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gtwrkpjbfj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gtjstvlvqs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gtpznjopih.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllerrxbe.html


<!-- 参考信息 -->