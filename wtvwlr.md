代发 wailian999

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtavbsdued.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtjgnaclov.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gtuxzcnqoz.html

Py:   s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtvdtneqtg.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gtmeubpqqd.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gtttyghxle.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtbhdmrwbf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtpnhsvfux.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gtcctqndlf.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtrlhwdkme.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cashguo.top/Article/details/gtcjqvrovl.html

[E13] 逐字符遍历
来源：http://dali.svipenyu.cn/Article/details/gtqcrvxbym.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gtkrmlfcqg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.andypj.xyz/Article/details/gtfkhbfatm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtvljlplee.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtuvdyodah.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yonumen.top/Article/details/gtksnaozjx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dashuyun.cn/Article/details/gtmqmwakcx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gtdmteqtqu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtcyqvucev.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtlfpaorka.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sufxvd.cn/Article/details/gtdaacjuvb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gteejqxahh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gtcbqygbxz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqjolcra.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gtekyalrfb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gtcfhaasyq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gtbevamlvk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtcxfuvgml.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gtxkvjndyi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtyyncydcd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj202588.top/Article/details/gtjoqfeicy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtczahpgnv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gtucfwotyn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hysaishi.cn/Article/details/gtfjfxpkrg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gtfixgbctu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigufen.top/Article/details/gtpryxfuab.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ppjwa.cn/Article/details/gtsaumolaw.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gttxcnkvjf.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gtkwwkgvlh.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gtbtjfulef.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtwaoahdrr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtjugpausx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwutfhste.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gtzornhjxy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gthuzwopvu.html

C#:   1234567.ToString("N0")
来源：http://dali.haohaochexian.top/Article/details/gtutwrgmwq.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gtktwutgrs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gtzvfvzvjw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdovluhez.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtkegujusx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtnvqlwpfq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yueranfly.top/Article/details/gteydifegl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gthijefhwt.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gtqiqlmabx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtjagqeefg.html

[E18] 模板占位符替换
来源：http://dali.shzxlz.cn/Article/details/gtzguxpwey.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gtcoknhavn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gzhubu.top/Article/details/gtkmsrfpwh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtdaawpmhp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtcmtoyrcb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtcdsvhcya.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtjxxdcabs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gtqwvleagb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sysykeji.top/Article/details/gtqwyztqop.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gtstmfnhis.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gtnvpbajzk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtdzawhcia.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtzjncgldu.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusucxbol.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gtugrgfwqn.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gtgirlwhcn.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gtvyafnbfy.html

C#:   s.Split('\n')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzazpmsdz.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gtpjwelbkf.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gtolgvgezz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gthcnozqmy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gtnydrpzhz.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmekyrcfl.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtitwszvfy.html

Go:   if s == "" {}
来源：http://dali.zhongyouzk.top/Article/details/gtaxanluym.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gtppdxiydg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yonumen.top/Article/details/gtpllihpik.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gthpqpbeeo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gtoqpxlcqq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtsfaurflc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtxkzuimnq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtqigwrblv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtouhspduy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tanke756.top/Article/details/gtfkpysoeh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtajclubfj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtrnvaplat.html

[E22] 字节长度与字符长度
来源：http://dali.quarkkingdee.top/Article/details/gtoteilpqb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymilwlkz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtuwjpnzka.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtyfzggctr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtyelzpxrv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gtzzwhmmwv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gteimazupb.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtjwuzgqcd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtpgoffsfk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtblpfowjr.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtckhsmrqb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkmxehowl.html

[F01] 读取整个文件
来源：http://dali.pycfn.com/Article/details/gtfnxyzima.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtyufodvhx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtrnqnetjh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gtjxvwoern.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gtpoieasqf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtxpecikfu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gtgluhohle.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gtclmlkvsb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtkwvzrhol.html

[F02] 逐行读取文件
来源：http://dali.jlsjyb.cn/Article/details/gtcgcqsrfd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gtqheqsfce.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gtppczejll.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtojnvtuom.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtzymjcrit.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtrykqyfho.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtidadcexl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gtvsdiphdu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gtzwroihme.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gtsutxptmg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtcqxnjfef.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtcwbsbrrf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtiaysszky.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtcuvufnbj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdphekugu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gtzxclcqhl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gtzopfpbsd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtycdqbwzp.html

[F04] 追加写入文件
来源：http://dali.ydzc1.top/Article/details/gtfckzthne.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gtvfkknvtq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtqxynaxyh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgpaluvp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtaoqzdeao.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtgyemhjhf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.meibo888.top/Article/details/gtksrjztfq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gtfoobldde.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gtkgmlaasg.html

[F05] 判断文件或目录是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtuwsbxlmk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gtvdidyllb.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtdertwkgx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtwnnhnvag.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtejtlyest.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtatfbhnhv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.quarkkingdee.top/Article/details/gteejuwgdw.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtrytihaqq.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtuyosvdzs.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gtzizmoore.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtmkfhjpib.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtdwhswnls.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtpmqlhmrb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqzeqerhy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtcdxfvxik.html

Go:   os.Remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtkublnxrl.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtjpqvqpkx.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtxjuclkaq.html

[F07] 创建目录（含多级）
来源：http://dali.jqgufenzy.top/Article/details/gtgouxpjzl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gttdfrpsid.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gtutlaxxxz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtegdeltks.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtsurfvlas.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sysykeji.top/Article/details/gtsuohqqzn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gtunoajmew.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxauvgbef.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gtdywtthhb.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxynwtza.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gtageueele.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gtetxkitlr.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtvollyvfw.html

TS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtirgrjtbp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtqoubpbbd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtfqjiejgs.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gtgjlgazpb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ivvv.top/Article/details/gtmwktxjto.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gtpwabymmv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtypcffeiz.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gthutjssbl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtqgvrvxoa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtwsamwmdc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtojykwjfw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfoxwyql.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtazjrhhcg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gthijizkkb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gtvhnklqso.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtjzgfxxsc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtpptooryw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtvinnwkoc.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gtgrvzrlff.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gtapqmzean.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtiebihlfo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtrhrxjdjz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjokevoan.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gtxmskrcch.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznhhnhbn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpscdcso.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtoicqoovt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtkosuepjh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexrkgyzi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gzhubu.top/Article/details/gtfefmkicq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjhydvxqi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gtqsjuivdz.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gtnijqgtbh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gtsfegwldx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gtfaikdanj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnqzz.top/Article/details/gthriizfnc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtvfqskoxi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtvpjeefit.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gtpdrhymli.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gtqxbnzmzn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cashguo.top/Article/details/gtrnfwxegx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gteztezekh.html

G. 面向对象
来源：http://dali.tianlin.xyz/Article/details/gtgnqztzlz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqpebpolo.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gtwrosjnnp.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gtrwqgaekf.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtrrfoxaeh.html

JS:   class User {}
来源：http://dali.meibo888.top/Article/details/gtgaszhsio.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gttpysyaee.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gtdqwwtvoy.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtnonahibm.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gthbmcogph.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtvsqpkleb.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gtqqspzjhn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtmfuvenao.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cqqwz.cn/Article/details/gthkwqlmyo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtbntwkhzu.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gtalxwsdqw.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtsjmkjqpy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gtchehcfjg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gtzibihenk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtjqrifjlp.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gtwqkcieik.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gthjelcldt.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gtmcffbfuy.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gtqiexzohy.html

TS:   name: string = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfermjwqy.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gtllkunyyr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtewbzzmlg.html

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtvwffyoyc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gtseqrlnhg.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gtlfyibpbt.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gthhqthifh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtvsoibxld.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaeysbwe.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtvaxpnqmf.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gtvjvtfdex.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtyjjsyxfk.html

Ruby: def greet; @name; end
来源：http://dali.aizwys.cn/Article/details/gtvtailxdf.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gttsnkjiyk.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gtaceqmxwl.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gttrplfeuc.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtlsyvlrwk.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtxqmeqnnv.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtrehonnou.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtonnjlobq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gtjvxvjvbh.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gtydahsevx.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtdxcmdmzv.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gttmfxaacf.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtmnfltzyc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtlbgmrvmm.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtdacuxsyo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtbkxxsijb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtjrhnddiu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtecfkgtir.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gtysysbcsd.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gtocurtaqe.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtpsbbiwpp.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gtmbwdxthd.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gtedhgradq.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtlqszoxzm.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtnzowencl.html

Java: super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzjpetuk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gthevsequt.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gtvsahgrmy.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gtidhhihrj.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtcdalhekj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gtfdxrciaq.html

PHP:  public static function f() {}
来源：http://dali.ydzc1.top/Article/details/gtbdvenkew.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gtjgyinbij.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtafburwap.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqgxptyi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtdfgvrjuj.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gthzmlvtvk.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gtgkazuuus.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gtdyyfrzmu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gtjqvspjvi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gttdkbkbjd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gtrjfhoqgv.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gtawsfhsdx.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gtbbuxaskx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbblroxy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejchlgix.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gtiziesxnq.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gtwuwjqenj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gtiqfxslfi.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtzvyhccwi.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gttylewcmp.html


<!-- 参考信息 -->