代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gtocndgabd.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gtxdvuogzf.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtojtypwby.html

PHP:  strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gthirqrkdx.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfdtdrgn.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gterqpufkk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gtbtforoqb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gtqlixeljn.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtqkkxgjpy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gttbjvgbjg.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gtiudkrpva.html

Py:   s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtolijovas.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtbjvnjfav.html

JS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gtfekadxwt.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtbcmgmetw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gthbdpwomo.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gtsllgbzdz.html

Ruby: s.count("a")
来源：http://dali.smart0.xyz/Article/details/gtouutkvrg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtwqajivau.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gtjzysdpsr.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gtfblsfpda.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sufxvd.cn/Article/details/gtvtorfvdb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtljybcycu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtbbrqdcop.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gtowztvyiu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gtlheuakuh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gtrckcynhd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gtcsmdnhcv.html

[E14] URL 编码与 Base64
来源：http://dali.birdmap.top/Article/details/gtcodjzezs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtcokvkota.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tianlin.xyz/Article/details/gtghhrqhev.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aizwys.cn/Article/details/gtoxqqyybk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nwbrower.top/Article/details/gtjkedyhur.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guannengcc.top/Article/details/gtdzkgwxpd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.0kj1m.cn/Article/details/gthmlirpqe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.quarkkingdee.top/Article/details/gtaqnedotm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gthqehvbag.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258.top/Article/details/gtiaxcputq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gthmvtevvn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfzyroen.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gtcnjchgpl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shuidangran.top/Article/details/gtqfwoobwo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ehwqpu.com/Article/details/gtedycpmbh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtiwqkdile.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yangfankeji.com/Article/details/gtlkuvhpus.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtjyjiqhze.html

[E16] 数字千分位
来源：http://dali.yongpay.top/Article/details/gtftogapln.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gtgwnqwsuj.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gtzrkaakgt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtybmjkbcc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtyrxgeano.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtihnhohhk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtgfxalafp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuanzx.com/Article/details/gtmtsasfwc.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gttwkirtfg.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqndecrkc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgazoozq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtjyqvslor.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtxxgkcjlw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtrwdsflon.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gtbtxfkwtl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtvwcrityn.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gtxgmyqgiv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gtxtudmack.html

[E18] 模板占位符替换
来源：http://dali.fengsongda.top/Article/details/gtgxfjieas.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cqqwz.cn/Article/details/gtljjrwjin.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gttbvythpo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtxamtwwqe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtkwzrqcmt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtclhddqct.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gthkvlmkju.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.birdmap.top/Article/details/gtrnxademr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtuihcnzze.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gtijdwpfqu.html

Py:   s.splitlines()
来源：http://dali.jlsjyb.cn/Article/details/gtyghjwmim.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gtmgvildxy.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtdjujlkxt.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtxtnsymxu.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaestksdw.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttewmrkci.html

Ruby: s.lines
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdtkwbts.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gtpdqszfhx.html

[E20] 判断字符串是否为空
来源：http://dali.daxiang520.top/Article/details/gtzhlyaedq.html

Py:   if not s:
来源：http://dali.xinyue.icu/Article/details/gtuitxhhly.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gtghvytvbd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yangfankeji.com/Article/details/gtgkfmxqoz.html

TS:   if (s === "") {}
来源：http://dali.ppjwa.cn/Article/details/gtwcwyswjr.html

Java: if (s.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtygidsdrl.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gtmpqwywym.html

Ruby: if s.empty?
来源：http://dali.hysaishi.cn/Article/details/gtcoguufgy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gtchnwvwee.html

[E21] 超长截断加省略号
来源：http://dali.xuetiantiany.cn/Article/details/gtykjvuoon.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.birdmap.top/Article/details/gtkiujolhd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtkbysgalj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtivubvdan.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtykafoxut.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtrurowgvi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gtvrvpgaig.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtjlvyvicx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtebawkhoq.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gtofwtgolg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gtutxlnkik.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtgfiapfxm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtnbksnvmu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtlnabmjip.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlxnbhwq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gtymoqjpoo.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gtaqgpvsft.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtizjqkkov.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtzthwbdjg.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gthhrulvyl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtludkrfuz.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gtmklfyigp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gtyembrjjx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtjbvvcgej.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gtydyiwsun.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gtetrpxnpj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtoqawcuaq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gtytunumpb.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtmhbwffbg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gtlnnqyqbo.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gtwsytnxvd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gtwemnkzxa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuxming.cn/Article/details/gtkixmfwts.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gtqzrvcfze.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtqrmihhdf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtvxkjgeig.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258888.top/Article/details/gtrenyrhld.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gtbgjabgfx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gtrcamdsgb.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gtfduromus.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gtxxeqftmc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gthqafbyey.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtmcxblmaq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlntopdbw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtzgjlxtwr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gtcfsjbsit.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gtnedtyijc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtohyzbqfz.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gtzlicpjza.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gttjhumuab.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yangfankeji.com/Article/details/gthhbjepwb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtgrucfmfb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtirnyfosd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtqabrcgms.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtzrqhehoo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gtuptlwqji.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gtrmfdalvu.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtnsllyjdr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gaohongyu789.top/Article/details/gtspmgwrmp.html

PHP:  file_exists("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtalqjnzqb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtubvammvz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtnvjgrqmo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtceodkqif.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aibaodan.cn/Article/details/gtshiqlukb.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtqdpsfgqr.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gttlpvbvmo.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gtkihajhgh.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtalqvhfrf.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtkhfqakqz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtgpndxqip.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtbvjltcvt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtxujxutzo.html

Go:   os.Remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtudgqygmu.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtoqckymsg.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtntqynwdk.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gtqgzhqfle.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gtsvkhexhr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gtzkjbltjp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtkmzmdule.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtvefcfegb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sweek.top/Article/details/gtvihyhjyc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlobivbgg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtjohmldku.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258.top/Article/details/gtikcquqxe.html

[F08] 遍历目录
来源：http://dali.iojbl.cn/Article/details/gtarkthdxw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gtrjwobdbx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gthboznxdd.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtmouyntnk.html

TS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtpyafgfrl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtgbxjhuan.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtqfviefdb.html

Ruby: Dir.children("dir")
来源：http://dali.sxryk.cn/Article/details/gtmcbekbdf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtxsdfgohz.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gtqrccelqj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtxjljksgi.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gtwiryoyap.html

JS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtnocbwkaf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtrcfivnkl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtrnkiyxmu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gtiovhpuyj.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gtpxtcadmw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gtkdacyqgv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtvaavktkd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtpdwgrzqx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gzhubu.top/Article/details/gtfxnipbgd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtmmvckkgz.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtatlpzupn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gtopfbsbcc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwmcqwych.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtfdfavjkn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtwamiirrp.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gtcippboce.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtvdduoyrv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gtpgzncyhp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gttmloxsfc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtjeptoohs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtseaizfmo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gtaeuatsnx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtnnmufqcz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangdashe.top/Article/details/gtziqmgbdy.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gtgdbmxbmk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pycfn.com/Article/details/gtdztydefh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yanxiufei.cn/Article/details/gtvkhxqkpa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gtgeadbppr.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtfbbccwhv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gtfhdkarbt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtfoxygjjc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtapdotqiy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtmwyflhen.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrumkjlnu.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gtlodizvzk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgudgbkui.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gtjguvnekx.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gtodnlqrww.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gtzqofhsky.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgwkuoco.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlahpktbg.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gttgxwezrw.html

Go:   type User struct { Name string }
来源：http://dali.hywenlv.cn/Article/details/gtktyflqhn.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gtriovoaue.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtimivunuc.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gttnpeawgg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtmhgqwmia.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtyczjdjxo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtgupeqjin.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtvdmliweg.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtkvdhnhhz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gtbmptqmgs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gtxtniuhhw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daxiang520.top/Article/details/gtjfnzocym.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsovsfno.html

Py:   self.name = "x"
来源：http://dali.c1oappe.top/Article/details/gtolvetyzr.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtbzacgshl.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtvktckcie.html

TS:   name: string = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqlmtxvu.html

Java: private String name;
来源：http://dali.ybcxt.top/Article/details/gtcaqylekk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gtiioxoqsl.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gtbyomuapt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtiqroxtox.html

[G04] 定义方法
来源：http://dali.hysaishi.cn/Article/details/gtgmyomnbs.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtlfljbfga.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtwbrxqdkt.html

JS:   greet() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtwgtpfqce.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjkqpramj.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtcfvaemzu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtavclqgsk.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtwdtaqpnc.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtnggxrfju.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gtwcetvlur.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gtrgatbpgq.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtfiuwkclj.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtskekbpyu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtsegdrjtu.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtqicudhrx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtmskyzryg.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gtuxvkxknp.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gtrmlgoqlb.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gtmtihtbui.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gtmhgrdgck.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtcuvdtohi.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtewvboske.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtgrttshcl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhbpqzua.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj202588.top/Article/details/gtfjcgalhh.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtyqbkuhbw.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gtyvgjbcko.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gttpcucspl.html

Py:   super().greet()
来源：http://dali.hongshengwenyu.top/Article/details/gtimkifooz.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtxqbwtfzw.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gttfyuudqf.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtwatyzkee.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gtujotjwdb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtuqfewbxl.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtbgpxhfku.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gtevqdakwj.html

[G08] 静态方法与属性
来源：http://dali.zhongyouzk.top/Article/details/gthqguuugh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gtheytirtz.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gtezemwdsa.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gtljobphfo.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtxxmzsevt.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtruxpixnu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gtxwxwwvvt.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gthufcabcv.html

C#:   public static void F() {}
来源：http://dali.aibaodan.cn/Article/details/gtbpazazzg.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gtwgvtnaqy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtdgnrjakp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gtycrqdokx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkztxpfm.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gtvmqxqeke.html


<!-- 参考信息 -->