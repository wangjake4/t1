代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtbxvtzyro.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtjkevjipi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gtijwomlms.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gttgyzqqil.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtecgggbkz.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gtdfnwdayu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gtqtlfggji.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gtkkiouyfe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhengqikj.top/Article/details/gtiupcwxzs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tianlin.xyz/Article/details/gtscymabsq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.bjfxy.top/Article/details/gtruelydpb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjqcuems.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmimgaohr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gtcqgcwnnb.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfarssqpi.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkmxtuot.html

PHP:  number_format(1234567);
来源：http://dali.quarkkingdee.top/Article/details/gthzvahvwj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtcrjjkiyb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpjnfsdh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkohilhhw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gtsruvocxk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gtokilwesm.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gtahlboigi.html

[E17] 首字母大写
来源：http://dali.jlsjyb.cn/Article/details/gtqwblzxru.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gtyqupminl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gtzzwohavo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtxucxkwzn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtribvbchy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtsofjxatu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gtxffombxz.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gtsrromcnh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sxryk.cn/Article/details/gtjzhftlvo.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gtxgzzotje.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gtqaltbmnh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gtolyxghfl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtjvdyvaoa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtbsshjsxs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtjibglngw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtsnuzofdu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gtbisgqshj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gtjdyibasr.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gtmxovwkkm.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gttlltrhwy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtgvsyzdsj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gtcserhwra.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gtvcuatdeh.html

Java: s.lines().toList()
来源：http://dali.yuxming.cn/Article/details/gtzjfcbxdw.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtksxcmuei.html

Ruby: s.lines
来源：http://dali.nanxinkj.top/Article/details/gtyfvpobcq.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gtrwvwayyq.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gtolduqpmw.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gtjgsvgiyc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pengpengdd.cyou/Article/details/gtjsgatlhi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gtmdwddsjq.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gtoanzoysa.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtiujkexte.html

Go:   if s == "" {}
来源：http://dali.yonumen.top/Article/details/gtryvdyind.html

Ruby: if s.empty?
来源：http://dali.c1oappe.top/Article/details/gtsawnkzps.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtohlenbyt.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gtyblsukff.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrikovdya.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtaeoybjhd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtfqdolhcd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtawirupja.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtseoorokr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ppjwa.cn/Article/details/gtdufalffc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gteegzquzj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gthomogsxk.html

[E22] 字节长度与字符长度
来源：http://dali.hnqzz.top/Article/details/gtziowrdwl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gttlsvtcan.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtigdatmfv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtxihujyae.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtwumkddby.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtanbhufbh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtxarbkfiv.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gttdxzytcg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gtsievswqg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgnmkzafa.html

F. 文件与目录
来源：http://dali.daria6918.cn/Article/details/gtdjwmabfl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtntqccrii.html

[F01] 读取整个文件
来源：http://dali.tianlin.xyz/Article/details/gtkkudvrvs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaawvjgk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtnexovjjn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj202588.top/Article/details/gtjjihhpzq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtstyxkqkp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtythztgba.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258.top/Article/details/gtaexsnmui.html

Ruby: File.read("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtnrsfwhnt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtunspbelx.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gtremmxuli.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gtejbctxhm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gtlezilbxx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtovbhrncv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthihqjhjg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtizdaujyo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hongshengwenyu.top/Article/details/gthipmkwyv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gtjqajvuta.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxdsuveev.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gtiolfnvwn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtawehgeub.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtvxxdydjh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtpwlqrway.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtmmiwhrel.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrimnldi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqczoluay.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqbzyfey.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtbgjiwuwv.html

[F04] 追加写入文件
来源：http://dali.daria6918.cn/Article/details/gtmumllqms.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gttygdoawt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gtmayaebmv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtzgywpqpq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtnmbxxbbm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gttmueiiuy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtyinmyvig.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gtayakzpbj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gtvxrjfbbj.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gtvgeciolw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangdashe.top/Article/details/gtxudwzvmv.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtcixyvcwi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gteusjoarv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtrnljdror.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtwwjgqtim.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gtbrdslpda.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtghnmbzaq.html

C#:   File.Exists("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtaqsokseh.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gtphrhpamc.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gtoexlkuvz.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtkaiqwlxc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gteitdkrga.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtkqcrxeni.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtjvjocryv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlhnvusz.html

Ruby: File.delete("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtwshkjmsd.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gthwwyryni.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gthpgqhgqm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gtvlngqzln.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yvedp.cn/Article/details/gtbbwsyxhm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtjqxecwik.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtelbmiaan.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gtsnfijnze.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gtqnhkcfkb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gtolttypqs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gtlocnpjdy.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwzqpvpo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gtwwuuvnml.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gtuwfkjhtx.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtcckdooqq.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtsliwaetg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtiasdwctd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.redwolf501.top/Article/details/gtibumaxak.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gtxfhvmnhb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gtnwcdrtrd.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtkpszdgxn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gthhbmqcvw.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtjacnisbw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtagisjbbz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtppyttrtc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtmuobhhgm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gtedtloajm.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtmvuzezil.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gtdbtqjvqt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gteccvpoql.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gthkehlgzr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hammf.cn/Article/details/gtfuaeuoxi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtnardyipy.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtoqqodvlx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gtaynodhye.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrskfrql.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtxqzftmig.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllwricgz.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqoleeru.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtnlbnuimk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtqrbysmsa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtserslbzk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtpivfiavr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gtjamgaayi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hongshengwenyu.top/Article/details/gthvlvvdeb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtbbocmykr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtzwbelfja.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gtdrraewqk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gtjabvkple.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.316326.xyz/Article/details/gtfernqulh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gtjkduzgfh.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtncqawnuu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gtxtsgbofm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtdkoqmasu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.mhx1999.top/Article/details/gtskxtidks.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gtmnnabfxw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtttttunbf.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gtpproawyx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtiwuungmi.html

[G01] 定义类
来源：http://dali.gaohongyu789.top/Article/details/gtlofnvdhh.html

Py:   class User: pass
来源：http://dali.zhongyouzk.top/Article/details/gtpgfogxqd.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtsumterkg.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtddrerjkh.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gthtijsadx.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gthsfodmfw.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gthclnlozi.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gticfjrnnc.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtjuydctfj.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtnlidofuw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gtebwkavze.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gtjjjgabyy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gteyifpnqi.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gtwpafbdyu.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtayfkmpru.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gtpkjouego.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gtvwemfidp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gtgigqupav.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gtzpboknfk.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gtyjxyaqtx.html

PHP:  public string $name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbdkwrjt.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gtckslnjxo.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvwiiemj.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gtzslrucfd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtdaguhdos.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkumjida.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.haohaochexian.top/Article/details/gtknmdskpe.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gtuwenopsa.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtutiodkow.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gteilodmnl.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtqtztjg.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtaygwekht.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtiunqgkmw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtmllymxbn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtkcxemfct.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gtgyvvqwux.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtgrirnsuq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gtgfiiohsc.html

PHP:  class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtgrnvdufu.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtsdhdpzto.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwpyqfpzl.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gthjbgduqb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjniubky.html

Ruby: class Admin < User; end
来源：http://dali.cucudq.cn/Article/details/gtysrhtrfc.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtdkylurku.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtipbqgyzz.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gtcrouqixk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtyoefpzxk.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbsjjkisg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtmyqrfdsn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtdxsgpjin.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gtsostuozo.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtxljvecxt.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtfoyvywsi.html

[G07] 调用父类方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxdcjqvl.html

Py:   super().greet()
来源：http://dali.hywenlv.cn/Article/details/gtcynlzsgd.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gtvcunckas.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtmkfpfsgr.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtgozivthw.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gtzxxmxbdv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gtyrqhlzor.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gtojwbpdiz.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gtykslnbdp.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtncetafmr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtlgocswkf.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gtpnucvfeh.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gtyzhmpzvy.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gteawvbvbv.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtydkobaag.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsqnonss.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gtdgdakmwe.html

C#:   public static void F() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahxwcnsf.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gtwpiltnoc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gtcllhxawa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gtsntwekhz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gtirnqzspq.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gthwolsebg.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtkuvhegbp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gthsizdhik.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgfzy.top/Article/details/gtoqfsgnil.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gtocqyrwzn.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gtcwohjprp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gtcwisgida.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtqzskimfn.html

JS:   #private 字段；其余公开
来源：http://dali.wangdashe.top/Article/details/gtehxsvcez.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtgfuftyhz.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gtgbunpqdd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gtlawnhury.html

Ruby: public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtpypzdvrr.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gtlrxeoonl.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gtmrjazijz.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gtvhwhgcrx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtxzgmnrrs.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuulgzijr.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtzceclibn.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gttmbcuxfw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtbngwoyrk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtdudlahwh.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigufen.top/Article/details/gtfunewvqa.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfhsklai.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtdbcexswn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtvyxdwabv.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtmihtkxxw.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gttalotqti.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtwpcuuekx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtwluvvzrr.html

Ruby: def to_s; @name; end
来源：http://dali.sxryk.cn/Article/details/gtmcxjflwo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtbdxeaebb.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gtjzzpakpf.html


<!-- 参考信息 -->