代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gtmszctpbs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gthefirmkp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnxiangtu.top/Article/details/gtoaqmzlto.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gtrmkamuyk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtymkscmnp.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gturorrhtu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.kuanghao11.cn/Article/details/gtuzjrrmqj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gtialmmtej.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gtkrchgmjh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzwkfxyg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gtedbzgnuw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gtsgzgnruu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gogol.net.cn/Article/details/gtgzftitjo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gtzlhzaqyn.html

[E16] 数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmnygyet.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gtoyillqys.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gtbsafllja.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtuaahdwix.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfrveosl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gzhubu.top/Article/details/gtbwrucnxp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gtntwnarmk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gtpmunznqx.html

C#:   1234567.ToString("N0")
来源：http://dali.yangfankeji.com/Article/details/gtajmqpffq.html

[E17] 首字母大写
来源：http://dali.chenzaomai.com/Article/details/gtbstbebmp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gtohoxmsbf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjgfnqbz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gtyxlqiklk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtvlctxiqr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jianghu66.top/Article/details/gtuszljrdp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gtrtvpndsk.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gtmyudguiz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nwbrower.top/Article/details/gtrsnxysrr.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gtcmjbxcku.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.316326.xyz/Article/details/gtjvlymnky.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gtpkpwvmjr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtsosluavy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtaentbgvb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtwslhirza.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtsignjatp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ivvv.top/Article/details/gtrhywjzal.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gotoacloud.top/Article/details/gtfvxagqbj.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gtkmlhveey.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gtodxgfjbd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj202588.top/Article/details/gtvxeqwpep.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gtomynqubv.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtwekwhxju.html

Java: s.lines().toList()
来源：http://dali.yj202588.top/Article/details/gtcqqbxkvg.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gtywxmmpes.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gtufwjesnx.html

C#:   s.Split('\n')
来源：http://dali.chenzaomai.com/Article/details/gtexvqrhzd.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gticrpofsn.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gtunyyngge.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gtkqjmhcsn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zycfv.cn/Article/details/gtqmtmemyd.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gthensxtpe.html

Java: if (s.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gturdbebmo.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gtcybqvhyi.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtsbqpbtpa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gtomipqgrd.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtwdoqgopp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gtecfsyxvc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtbrhutpen.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzgacqqy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtmkxkrhcq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtibxfcdch.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gtmeotuaiu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtxovyynem.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gttuaifall.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtgakrtfjo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gtzlcxphqx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtugmotxfw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gthccrloff.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtsaglkoql.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxqfbzvg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gtpochusmx.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcpdyrxb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gthdzpxceu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmgalqfrf.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtazunytfh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgykqrpak.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtghjzrdxt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gtdljturuh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gtqyijhols.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gtsaomnvbj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtxlufzfvz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtjdxmsnfo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gtirgltacs.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtappluqpg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtgyblveci.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gtnnvmgsea.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shuidangran.top/Article/details/gtekiyhmdw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtzxqffroj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtdimcolvu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gttplesbqh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjuyghfe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gtxqqoiwby.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gtyrezmccp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gtzoynliex.html

[F03] 写入文件（覆盖）
来源：http://dali.tian-w.cn/Article/details/gtjlvjyrsf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtvqfxmuvv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtdntcvezz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gthtbpolcr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtzgwfpicn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gtryfgmqun.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gtbmwitnsv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtrwbdgnck.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtstoyaelk.html

[F04] 追加写入文件
来源：http://dali.gzhubu.top/Article/details/gtfhqujajx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gtqngvwltu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtwwazrykz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gtitmlugxv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtnxzvlaby.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtolelweeg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtghbgxtdj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gtdkwnyotl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gtsdpfmjsp.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenlongwang.top/Article/details/gtmlussiop.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gtwbizgzra.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtjwejpjdm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtoktzdjag.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtefzpdzlg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtfhggmlqc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gtdovikyzc.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtsofbnalw.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gteskdqzwx.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtyisornhd.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gttqnsobls.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtdfdymvkt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtkyrxqtah.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtkxcuojmu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtbdwvwbcc.html

Go:   os.Remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtmpvyswdb.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtvjzfdhry.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gtrnzzdeka.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gtljcezdrl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtpcjtdzqb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhoulong.xyz/Article/details/gthvgmpveb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtludyabrz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtwjxbzuiz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gtkgqvmdhx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cucudq.cn/Article/details/gtofqklntc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gtmexodcmi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenzaomai.com/Article/details/gttqjrpbbt.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gtyhhgbdcg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtpigglqyj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gtqjtrtzor.html

JS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtyngvngvy.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtdsscyzqs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtgkglnhcs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtbeghdnht.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gtpkhtysip.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gtlfmfjarw.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtcfhsojvs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtmnxfmpuk.html

PHP:  filesize("a.txt");
来源：http://dali.meibo888.top/Article/details/gttggzoket.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gthgujlxek.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtslhcjclo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtziclrnkh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gtqdfgjqqx.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtsewnacrx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gtjjbdksbs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gtlnhvrnfw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtbvylchpn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtyvchinaw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtvknoghsm.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gttikrxbkg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gtthzbbaqk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtcasplwhq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtvwgwjbfd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtgqtgijcc.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gttgqoevtm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqnrkgjin.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtqucfnwkt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtiiucexvn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtnnhlhjox.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gtsthxvyio.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gtnchboppl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtrgmyhocv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gthbzavinc.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtixbvvmyz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gtphtrhhad.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuanzhike.top/Article/details/gtnhyoyunf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuanzx.com/Article/details/gtwkeznufq.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gtvnergyoj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gtyqjzejkc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.9152youxi.cn/Article/details/gtnwhiyuyl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtdkufpcan.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xinyue.icu/Article/details/gtpkhzoesg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrmqxextm.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gtmjcwobbx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdwdzkvyl.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gtdrjcauvg.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrbpbvwe.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gtgitqznmd.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtummqzigs.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gtuvygyzgk.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gtkincxpgi.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gtftjshjor.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrykdzlkd.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtripfdgqa.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtbcrqqfeb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gtdcazdqam.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwaqoiccf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtfqzitjhc.html

TS:   constructor(public name: string) {}
来源：http://dali.sufxvd.cn/Article/details/gteusonrko.html

Java: User(String name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtqgmqeled.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gtxuafsvhu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tian-w.cn/Article/details/gtfaduptoy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtzkfdiklm.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtkuwjvcff.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtkzxxasxk.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gtnngbdtgw.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtiudurwjo.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtknrzvtlv.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtzfumrzmy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gtjadeztrp.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtidzgursc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gtpiamxqwy.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmjxxcbs.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtpdpwbpxl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvvtyibb.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtrbjhkcle.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtdboyrpou.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtqsvukvea.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtacrurmyf.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gtoqeviptw.html

C#:   public string Greet() => Name;
来源：http://dali.cheryme.top/Article/details/gtldgddgno.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gtlfylakif.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtenwmrogt.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtderfstfd.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtznjasomq.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtwrgnxghv.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtzsdhtrpu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gtkwguexsv.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gtqoqpihcs.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gtllgkuhfy.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gtfdbinqir.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gttmzznohh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtkvipstkf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtyerqojzp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtpoamyeeo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtsbulcxoc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtkfykbvwb.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gtbzllnowy.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gttmdhkrar.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gtnihxpnfp.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtojgilrgn.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gtougtemow.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtxvkcgkuk.html

TS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtgideujxd.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gtftonrosb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtlttehira.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gtepgnyurp.html

C#:   base.Greet();
来源：http://dali.xziqi.cn/Article/details/gtfjotgxmd.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtomifndyw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gtvolrcvza.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtvxkhbmxc.html

JS:   static f() {}
来源：http://dali.iojbl.cn/Article/details/gttueilhdo.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gtkuquljzo.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gtwriiqahf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ppjwa.cn/Article/details/gtaxzsldfn.html

Ruby: def self.f; end
来源：http://dali.hfpthk.cn/Article/details/gtvkhmtujo.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtioqhpcfu.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gtjvnpdkiu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gtapoljoyc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gtmidcnmjn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gteqgtvafd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtjfyuspet.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtoawqisrw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gtkzfcslev.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gtjdjnecjl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtsfyqcnvx.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gtoymkzcob.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cashguo.top/Article/details/gtdlbupppq.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtuohhzjyo.html

JS:   #private 字段；其余公开
来源：http://dali.jyoumei.cn/Article/details/gtsddgqknp.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzvvftez.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gtvflxnheo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gtwqjdfeyi.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtxqzwhtak.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwczlowr.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gtvglkxvul.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gtnojlspmk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtljewqfkn.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtbumavkup.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtaixytgbc.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gterzusqcj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtanoxeieq.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gtvbvykedf.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gtdjxywnhu.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtypooawxi.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtgchdpbzq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtlniajuak.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtggiajbeu.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtjraudfao.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtanoxddoj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtgmlytlxm.html

Ruby: def to_s; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtsrhtgsow.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtzifavulq.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gthlietzqr.html


<!-- 参考信息 -->