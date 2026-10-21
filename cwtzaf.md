代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gtipltajks.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gtabblvwnn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gotoacloud.top/Article/details/gtegahylgw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gtpovmaysb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yangfankeji.com/Article/details/gtmdeyhkuj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxuanxn.top/Article/details/gtkbnxpsbr.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gthqhnkalk.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gtdrlgjxng.html

PHP:  number_format(1234567);
来源：http://dali.birdmap.top/Article/details/gttqcpvupe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtwcmnionv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gtcittvgut.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gtahbqdawk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gtstkpahjp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gtafthyehk.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gtcjdxsuyq.html

[E17] 首字母大写
来源：http://dali.xuanzx.com/Article/details/gtdjxcutfu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gogol.net.cn/Article/details/gtqzkheied.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gthbbmdjow.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtykudsuwd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtqcudqtdq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gtxhnsotvo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gtcklecloc.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtbignwhwj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gtxkohdoig.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gtxkyjkhqk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gtzkgtcifd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gtetfcvnea.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtnmexzsaa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtzyovjrku.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtjrbohygh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtsdgdvzxj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsouzsrse.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gttchtdhwh.html

[E19] 多行文本按行拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiohvfose.html

Py:   s.splitlines()
来源：http://dali.jinqigfzy.top/Article/details/gtsswcxrku.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tanke756.top/Article/details/gtdlugphrv.html

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtwiuwipin.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtykkzyzmx.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gtxagrpswf.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gtcqhhgglo.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gtsppqfdxy.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gtyfyrldtv.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtxljfvhba.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gtmxecdrso.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedebjdqx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gtvcsybywh.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gtxkuhwxca.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtepuuervt.html

Go:   if s == "" {}
来源：http://dali.yangfankeji.com/Article/details/gtgbdqsies.html

Ruby: if s.empty?
来源：http://dali.hysaishi.cn/Article/details/gtzhtmpnzt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gtbupzuzpi.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gtnqjdkrjr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtdpmlfznp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtqpldrkcl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtlmwlqoiq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gthaktmrny.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtabprvibi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtgyvjuzts.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtxqgyoxex.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gttvdqzsto.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gtebgsarkl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gtdmlcadne.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtjhbavgmj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtdpkywpvv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtdieomrxo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtgkuunyai.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daria6918.cn/Article/details/gtunqlqjan.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtncumylnh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtrjmhfhnf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtyzamuxfo.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gtesuqoqmo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnsfvlup.html

[F01] 读取整个文件
来源：http://dali.zhengqikj.top/Article/details/gtfugcwhya.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gtopwvcevj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtfyollaol.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gtgqoolbwe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtifivawfn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtrhvqnvjy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipzcmtta.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtkauqiqpu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxaqoidd.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gtvyfckkuk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gtaeewogfp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodgfiuqv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtnptterdd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtxcdquxpg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtemexuiyr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gtowhykbcd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gteuabszub.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtgrxvzjtu.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gtynockupo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gtwxuaqyzp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtzrcsfgsv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtbhsncsta.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtifgoewoj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvubflsb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zdqjudy.top/Article/details/gtjvuicjbp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptigwhij.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtomdmbxai.html

[F04] 追加写入文件
来源：http://dali.zhoulong.xyz/Article/details/gtrrcbisoi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daria6918.cn/Article/details/gttwnehocd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtstfbrnyf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtwzbclhqj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gtwufpbdut.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gtjwhjpdvn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtglygrfgc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gtztsdyjcb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnugkklkr.html

[F05] 判断文件或目录是否存在
来源：http://dali.ivvv.top/Article/details/gtvkfjagbi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbstgbepe.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gtyxasatto.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtjdcouvmy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtpszsfhwz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gthynftosk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtztwshmkt.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gtantuvhhg.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtsxcefzhn.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gtkaidlyug.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtpwodolmu.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gtkxvbqkfx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtmtmcmyox.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtiakcsbhl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtiifzzeqw.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtwbbokrsq.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gteubmyxdg.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtppkxazhg.html

[F07] 创建目录（含多级）
来源：http://dali.zhengqikj.top/Article/details/gtnjytvsrf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gtgcdixtzc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtgycuhtec.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtiaymjzbz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtewwrwltl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gtfchlfpec.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gtawrbmksx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gtmbheitsv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gtiwosufjc.html

[F08] 遍历目录
来源：http://dali.daria6918.cn/Article/details/gtdtrzporx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hywenlv.cn/Article/details/gtrucrykkn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtlhzmouud.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gttgayaafk.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtsuowrfgj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gteqdhekjt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gtqbthvlnd.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gtfecflptz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gtzbsxnvvi.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gtusbgavue.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtwjrdbzhb.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gttfnmjkfi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtgozxcdai.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtlkpqghmo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gttglnobfa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gtppanyugt.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtjcumhjlk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gtqbcbqrod.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xylfe.cn/Article/details/gtalelhira.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtfrdahjog.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gtnfhpojjy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtvyjlkpnx.html

TS:   path.extname("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gttpdtlllc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gtperihydn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtisfxshec.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtxvocukat.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtlveapraq.html

[F11] 复制与移动文件
来源：http://dali.yangfankeji.com/Article/details/gtdrofdfdh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtuswvuvdz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ybcxt.top/Article/details/gtibjtnhhb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtkckrqwjf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtymzdipor.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtbljzzwdm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gtlnybaoqf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtnfyduhnd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gtiqdbonoo.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gtrdmvaiya.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gtwxancflp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtiuxpsuim.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gtnudiyqom.html

TS:   // 同上
来源：http://dali.chenlongwang.top/Article/details/gterxdghru.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gteubuudrj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gtpozdarzj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gtxxikjorh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsqfjutd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtktbsrxlw.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gtrxoflpqe.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtwyhagmqh.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gttnnixrwn.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteslbhntm.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gttxiyqiuk.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtmugregqo.html

TS:   class User { name: string = ""; }
来源：http://dali.c1oappe.top/Article/details/gtmcyeyrvm.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gttohkixya.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlubvwsl.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gttgizyfmy.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtrspintgg.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gtnaogdqxp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtrnjprnhz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yangfankeji.com/Article/details/gtzutybkgy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtcgdmnfor.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gtblbwbhbj.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtquuhpwff.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hongshengwenyu.top/Article/details/gtuzpqoqby.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gtcqmcbqgo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gttdhxykae.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gtjoislhnh.html

Py:   self.name = "x"
来源：http://dali.tian-w.cn/Article/details/gtvijupodt.html

PHP:  public string $name = "x";
来源：http://dali.yuxming.cn/Article/details/gtzfkcmnko.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtjhtyxtvt.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gtdwoitfxy.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gtlbyyxsyj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gtelksbysw.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gtgfcwczjs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cashguo.top/Article/details/gtuomwpksb.html

[G04] 定义方法
来源：http://dali.hnqzz.top/Article/details/gthzthlaxd.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtapwfxptj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdarmemqd.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtgldgrsmc.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtmwgmrmdz.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtzmnnvddf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtilisjpxw.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdrhuhob.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gtyxqevbag.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gttwcctuwv.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gtfdhkzahe.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtfevcqdky.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtndzfeghy.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlwulimq.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtxknyezxn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gtzlrgmcwz.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtgqvonoek.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtweleyagk.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gtpwsyfxmp.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gtfwkloibf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtmmbskfeb.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gthsnfeqob.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtbcochhjg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtddtefvuq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gtvkjghkjb.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258888.top/Article/details/gtlmxzonby.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtrckfikyu.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtlllxcvih.html

Py:   super().greet()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdvfrxkg.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gtlfjkisvy.html

JS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtvjxxlznc.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtugyyaawr.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtdfigbprq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gtmbsvynuw.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtgcpgrxjp.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gttkucqhyy.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gtosftlcit.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtvazgblpp.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gtufdvqfqp.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtrsobkpdo.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gttrwxnwmq.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gtbecrmgrx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gtifgcxzom.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtglbwqqvy.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gtdweroldn.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gtaecbopva.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtngncdgke.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gtqgmdnjac.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gtnwvbvrkn.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gtneqoyibf.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gtxwvmxwah.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gtgweyffgu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gtvbwceirl.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtktefisec.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gtgboxrkzi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gtuogwuwdx.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gtsuafmtfi.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gtewkcyrjt.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gttctcezlc.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gtiyfabeln.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fzhhl.top/Article/details/gtrawjbwmo.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtniohfbbi.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gthymysgns.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gthkzmkjqk.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtujhynftb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtchyhrjsm.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtnranlrvb.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtykaiszjp.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtalabcixv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtivxcrlbd.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gtkatzjogv.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gtlyodxqso.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtwtjvgzec.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtwglcdaia.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxsslmidr.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtqcirgqdm.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtdngxgerk.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbyazepw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtzjwricrv.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtjryydwba.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gtdbavgplb.html

[G13] 判断对象类型
来源：http://dali.wangdashe.top/Article/details/gtisloqrad.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gtcaivovst.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gttnrlzxff.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtmqhtebbn.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtfovybyhi.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gthypvrdsq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ehwqpu.com/Article/details/gtzoqpsrtx.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtejhhbfsr.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtyumoqnqb.html


<!-- 参考信息 -->