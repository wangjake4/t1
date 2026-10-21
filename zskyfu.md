代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gtmmjkwuhr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ydzc1.top/Article/details/gtbpmamvbe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtzfolsuhg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtyufnefat.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sxryk.cn/Article/details/gtrrysdmpk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gtlywbhako.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gtdhmhfrwj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gttwzpreid.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gtkcnthmlk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmunprkf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yvedp.cn/Article/details/gtvnbqzhtr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuanzx.com/Article/details/gtdodwtwhv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuanzx.com/Article/details/gtokbwmlfv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtitqgbcxx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gtbqgbxhwm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.meibo888.top/Article/details/gtvcycjwad.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gtkvwtkdzn.html

[E15] HTML 转义 / 反转义
来源：http://dali.ppjwa.cn/Article/details/gtezxbchwo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gthytgmdar.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gtjwebfspx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gtvzdhrcfa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gtwlssbmgh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtbzugogmr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtdlifardr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtwieywxql.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gtxqjeaeiw.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtkwwhfzev.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gtqgcwlvka.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gtgrgnbuao.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtpivjhnax.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gtnwebamxh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtjwrajxrg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gtfxwmkvxi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gtveyhetvn.html

C#:   1234567.ToString("N0")
来源：http://dali.ydzc1.top/Article/details/gtsrrvmzan.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gtcftcjacz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hysaishi.cn/Article/details/gtejwjvjay.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gturvlcglf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtaipdftqh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtnaivinva.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gttoorwjlo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtlfhvxdey.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtwmammrai.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gtjrvqnlya.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gtjsjqtqnd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tianlin.xyz/Article/details/gtiemugphi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gtenybsjnb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmaunfjpu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtoqgqlzxj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gthxdjcpts.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gtjdxzicib.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gttifiyqfm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cashguo.top/Article/details/gtcmbtbxij.html

[E19] 多行文本按行拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjxwbrhh.html

Py:   s.splitlines()
来源：http://dali.gzhubu.top/Article/details/gtoslgrpos.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gtfgvvqoun.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtjwuigbcr.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtzuigkfmc.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gtcmyiztyb.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtophycvju.html

Ruby: s.lines
来源：http://dali.zhiwuduotai.top/Article/details/gtpovefjdc.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gtbqzyzwhw.html

[E20] 判断字符串是否为空
来源：http://dali.smart0.xyz/Article/details/gtycoaxarn.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gtndaekwrl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtpjpacfzn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtpjwzuywd.html

TS:   if (s === "") {}
来源：http://dali.ppjwa.cn/Article/details/gtrfzclayb.html

Java: if (s.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtcjlxojwu.html

Go:   if s == "" {}
来源：http://dali.zhixingplan.top/Article/details/gtkqsclnbw.html

Ruby: if s.empty?
来源：http://dali.daria6918.cn/Article/details/gttqathxsi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gtbjfqsktv.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gttboluggz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gtixscoiae.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gturnseaau.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtdfdlultq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtxphxydjo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtieumgcak.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gtjvaypasq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtmzlbnmlr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhxetawl.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazyhmooh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gtexeffuxt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtvtuebgty.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtdwpbgcfy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtsixhptwn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.c1oappe.top/Article/details/gtekxsnlub.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gtlfgrqfyv.html

Ruby: s.bytesize;  s.length
来源：http://dali.c1oappe.top/Article/details/gtqepihpxe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtqlbecrkb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwomjiuyq.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gtdyowzwmw.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqhrbgdfs.html

[F01] 读取整个文件
来源：http://dali.nanxuanxn.top/Article/details/gtpcgrnyjd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gtnjgzpxse.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtpcijfhkd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gtxkiqwvfr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gtfcsgrjhk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtbsbawafx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gttxzeqzla.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtblvbztmn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtqdeouxac.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gthclueqyl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gogol.net.cn/Article/details/gtgtvrymjk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnxiangtu.top/Article/details/gtdzvsdenn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gthdrhplvc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtyyizdhyi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtepchdpjp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gtcmbpxkcf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gtaqymucbg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gtbbaouafc.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gtmattuyng.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gtwjhexsvl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtkacnrrpz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtxgbixhsa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gttemfyqze.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gtbukksxef.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtplzxobgp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gtfbuxggte.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtibvyvbpt.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gtilsdjqfy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gtdcfqhcfc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.0kj1m.cn/Article/details/gtwavvtauq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtuyqzmazm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtrimjxdaz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gtqethqipt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gtqlbdhnns.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gthvrhyhab.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gtlhmwkoap.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtbfcxpjrd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yonumen.top/Article/details/gthkbkkdsl.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtuszphsyv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtlgeshpco.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtcedzimrk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtjexpzhui.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gthxormzgs.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtodkjktqz.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmxbparz.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gtmdzywgmh.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gthvitjvya.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtnhkeiotb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtgomibuvn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtgtxduvgf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtdxjevxtg.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtrwusrnlt.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gtauipsext.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtcbdtmjsp.html

[F07] 创建目录（含多级）
来源：http://dali.dianchejie.cn/Article/details/gtdwuqrqyf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gtuvgbqdkt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gtleianrnq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtkfjffvgp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtxjkdgcgh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gtncejmgzo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gtxzekdyed.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtoyttsgbh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gtjcdjfrxs.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtshczpmxz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwkikghn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcehganv.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtzkheecnt.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtqtnqcvlz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtrhumlxgu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gtjtzpwsvu.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gtwuvyukhw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gthyxiyofn.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gtwnsderyw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtlualtiek.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gtzjrnmnbh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtxyiccggn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtzujzelvm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtogodjzdy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tianlin.xyz/Article/details/gtkpnthmie.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtkcuoimps.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gteyyfllya.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gtdsbxbnax.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gttajnrjue.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtrxuguglc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtgdboogxp.html

TS:   path.extname("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtcfvdggof.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gtxgcybmoc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtcmfokaon.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtgcuomryp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gthgsjolfc.html

[F11] 复制与移动文件
来源：http://dali.pengpengdd.cyou/Article/details/gtrtjzulmw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtztzvmbia.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuxming.cn/Article/details/gtiahzuisy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtyvpvtrtb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtdymgzqgg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gteclimxzr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gtqgunvodi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtbkzhdqde.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gtkzhgkpwh.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufbftbca.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtodsvkjje.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gtabjdxrad.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtbwjwipiw.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gtmqpjihtw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpuwiqlt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ydzc1.top/Article/details/gtdeesquti.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gteiwlsaot.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258888.top/Article/details/gtjkcoqact.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtgribigzx.html

G. 面向对象
来源：http://dali.tanke756.top/Article/details/gtifmtimsj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtgfnumoko.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gtenfxtpoq.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gttjavenry.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gtnpbibxff.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtcowcrxdv.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gtpxzqpakl.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gtnnqwefnb.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gtmizpetss.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtrgbbqglx.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtdvudcyyk.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtjayfqfbl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.meibo888.top/Article/details/gtwaucqbsy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gtfsohgmrn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtrvhpujxc.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtyqaifjjl.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtxlcsplca.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gtpxhiqrrm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gttyccgjhw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtgmazdlkr.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gtoxtasinq.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gthulbhlyg.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gtwaatzxgx.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtduyahjnt.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gtnshnotyl.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfamalmii.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gtjyqlkrxn.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdqmrqje.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtmwscifoi.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gttylofmyx.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtbwfebgdt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtgulfklgt.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbqynyhid.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtnijkkscy.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtpfxghqyi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtemveroua.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gtohnttqep.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gtirmsbamv.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gtiwpreufv.html

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gtxweokvxh.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtbnfmtafu.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtfkrjazoh.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gthhbvgilo.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gthawcdozg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gtgwfwqkjm.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gtqwzsjiet.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcyniretb.html

[G06] 重写方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwoswujsn.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtfwbjwpzj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtcitsdjah.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtyeempzwd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtorxdhcia.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtgewgennc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gtsoqwreuf.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtesbaplbo.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gtwmignlsu.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gtshannqct.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gtcfwpevel.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtspflvevm.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtpiexvfke.html

TS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtlicxdrzl.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gtlkgwakkr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gtphbsecbu.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtuejbpmha.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtnskoieio.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gtilouaigt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gtkhvkymif.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgjjnrncy.html

JS:   static f() {}
来源：http://dali.ppjwa.cn/Article/details/gtpeswuvrr.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gthcvyfrwy.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvgvthrdh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtqeyskyiv.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtqipoifrp.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gtbhxpyvti.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gtsstgjqsy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gttuicuuxc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxobjhuvp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtzbffplvy.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gtfwntpppj.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gtjcmtlrnk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gtpwxvatse.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gtnbkyugag.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gttpibwcun.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gtoqpwwidl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gtqzvyrame.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtudngmogw.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtfjygawci.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtwhnzzizg.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gteiufumnf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.meibo888.top/Article/details/gtdxvpmipl.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtobceivon.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gtbiqemesu.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gtdgnrycaq.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gtcnhhcmzi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtwbnlexfs.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtvznxrbzx.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtvqpmrbbf.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtqikldohm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtgghvteyv.html


<!-- 参考信息 -->