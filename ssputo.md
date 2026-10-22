代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.bjfxy.top/Article/details/gt2dovtcbwu.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gt2nngfcvzx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gt2viyubunr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2ltsjlmkq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wygwypfs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yongpay.top/Article/details/gt2zqthdvyp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gt2lyvbhxue.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gt2zpjjaegb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gt2wkdhiqfi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daxiang520.top/Article/details/gt2lpfsrxob.html

[E16] 数字千分位
来源：http://dali.guannengcc.top/Article/details/gt2qicslssb.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gt2vstxotok.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gt2wzpdtijs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gt2hoitvwhd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2xzbwavry.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpahhwxa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gotoacloud.top/Article/details/gt2ugvgewju.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gt2oweyddwc.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gt2bmoeacpb.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xocotstn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gt2hrbwftpa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmrkemik.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gt2wdjxwwxx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2kfgaglkn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfkrabnj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gt2uakqotyn.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gt2gdtmwhab.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jianghu66.top/Article/details/gt2ytvyrnli.html

[E18] 模板占位符替换
来源：http://dali.bjfxy.top/Article/details/gt2yyvlqsdw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yongpay.top/Article/details/gt2cdnhurtc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yangfankeji.com/Article/details/gt2msmtxpqk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2veuoxdqa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2trydeefo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2dnwupino.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2ekymztrv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ppjwa.cn/Article/details/gt2ghznvphc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gt2gvssjyvf.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gt2xvisgteo.html

Py:   s.splitlines()
来源：http://dali.jlsjyb.cn/Article/details/gt2zjosuavv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2edcimrkd.html

JS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fltvtmqk.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gt2jcmniibt.html

Java: s.lines().toList()
来源：http://dali.jianghu66.top/Article/details/gt2iogbxrxr.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gt2mcwfmxnc.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gt2bjmalvhl.html

C#:   s.Split('\n')
来源：http://dali.0kj1m.cn/Article/details/gt2ztjdzrib.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gt2cdyiyrcn.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gt2xazygnqu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zdqjudy.top/Article/details/gt2kawypkgm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2yekxolnd.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gt2omsydlha.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2qqhxseyw.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfaytstp.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gt2ztniydqc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gt2hnwxwtnu.html

[E21] 超长截断加省略号
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgphklsw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hongshengwenyu.top/Article/details/gt2iomrfpdw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2kjjqmxgt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2pimjvwgf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2izekskxy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2fyfnyymz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gt2vurzesng.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2vhbrjogz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gt2qenczwaj.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gt2uloepdrv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2chycrwsv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2vxmesujj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gt2rpzdmhtw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2zryssgrj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gt2ikkndpcu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gt2fzweokmf.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2prpsxspv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gt2lrxziwwn.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2cdhkmvth.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gt2fnyjgaxf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2olsazaef.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gt2yvzvrzah.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gt2yhjufvol.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2tgcacnop.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gt2iakjxdwd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2lvfygwhf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2ciaabqjq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gt2fdzjzvfc.html

Ruby: File.read("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2yoeslehs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2oeicsmhh.html

[F02] 逐行读取文件
来源：http://dali.9152youxi.cn/Article/details/gt2qensrilg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gt2bioqcctw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yanxiufei.cn/Article/details/gt2bbxiyjnx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2pwintmrk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gt2mhsuinss.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gt2jpwewzup.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gt2mwngrzlf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gt2uqalwztv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gt2dxgeccif.html

[F03] 写入文件（覆盖）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfrusjbz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gt2qmarkgjr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gt2izwkbklz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2vroyazvq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dddsvjdg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gt2qytjmfok.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gt2nhfodrfz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bznlxkae.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2oncqydje.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gt2wyqwilrs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gt2twpcfbef.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gt2dkwklzah.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tddadgeo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gt2hlkjqguo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gt2gsokzigx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.iojbl.cn/Article/details/gt2yimpngwy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gt2ceztjsdr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gt2huyhowww.html

[F05] 判断文件或目录是否存在
来源：http://dali.daxiang520.top/Article/details/gt2tfjvtset.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwsufarm.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2kwhpbihy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2hhllabri.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2mfrsadpd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2vxxypmtg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gt2bejbobsz.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2skarubku.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2emlfakgl.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gt2bqxfklso.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jssdqemj.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxwplovv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2vouaycgy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2vnyfbvfm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2kmqkpzdk.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2lhlwmopw.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2cawwrhra.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2ysawtvho.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbtzzlvs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gt2fyhkayrf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gt2numeaejq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2nppabomz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gt2yqhrtcle.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2fnhtberw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258888.top/Article/details/gt2lhmqwkkw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cdnleiting.top/Article/details/gt2oakcwjno.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gt2fsvfrcis.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gt2arlarylz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gt2btqadkka.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gt2qujalhzh.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2nbzypbjc.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gt2nlzuopkp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gt2pvishlpm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fengsongda.top/Article/details/gt2ccbvljwq.html

Ruby: Dir.children("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2nwygfvvo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2btxktluc.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gt2zuafbqac.html

Py:   os.path.getsize("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2cosvdjua.html

PHP:  filesize("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2crwyxpik.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gt2xnodpuru.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gt2wgmxekfi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2xyoywwok.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gt2kpehlvwp.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2szdxpatu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gt2bdyqafmo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gt2jrztexlv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2nvxphaty.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2unlruvch.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2dkmmcjnq.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2rcqsxefg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gt2tipcpyzh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2qtzdfybr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2hdofzfrh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2grizkczr.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gt2lgoowyde.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2pbxxllro.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2ibrjahak.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2dkppvpbp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2oqzvquxx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gt2bcatzjvp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gt2mybpfbur.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2uhpapbsb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gt2fbndotmp.html

[F12] CSV 读写
来源：http://dali.cashguo.top/Article/details/gt2dlsnryhl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxinkj.top/Article/details/gt2xzfxmrvc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gt2vfixuzpg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gt2wrivluiq.html

TS:   // 同上
来源：http://dali.daria6918.cn/Article/details/gt2umtvbbpm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eiedqjan.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gt2jtrhujte.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gt2dlporqzd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gt2udgyozwj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2sykaavtz.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gt2opoelmlq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxskaxel.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gt2eagtvivy.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gt2hbhrxbrp.html

PHP:  class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2luvefwxg.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2wxnlrolh.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gt2sxbptgrr.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2dqhxquwr.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gt2snmxyuqn.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gt2augtrdxl.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhfgyhhx.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2njasfjiq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gt2degjpflw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gt2iytqytuy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2cvkltorh.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gt2nxaemlcl.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2ytfdlzaf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gt2dnepsxnm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gt2ojjfrtln.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gt2kzknlazg.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gt2rwpkataj.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gt2kcjiayhl.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gt2oylosfhw.html

JS:   this.name = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2ucjctagv.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gt2zmsmhndy.html

Java: private String name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxzvbcdc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gt2cpbvwynt.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gt2gscsskdy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cgezuvqf.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htsjsjzy.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gt2zcndhcmv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2labxsqfb.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2flggzhzf.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2cjtqwipl.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2rmypjaqt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2klaihnxj.html

Ruby: def greet; @name; end
来源：http://dali.bjfxy.top/Article/details/gt2lbnzcxfh.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gt2wmpqgvkm.html

[G05] 继承
来源：http://dali.jianghu66.top/Article/details/gt2fgnmwqkn.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gt2dgxvsric.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2lqkzcndb.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2eusmuqgt.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2regfkkti.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2cyzgaeve.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gt2ksnstmpa.html

Ruby: class Admin < User; end
来源：http://dali.xinyue.icu/Article/details/gt2oixkxfut.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxrwthmc.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gt2kvuvmdry.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agbffzxx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2qckvvlks.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2orvlseim.html

TS:   greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2wrnungvy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2gbqbrkiu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gt2rgezrvag.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gt2jzbolgxq.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gt2mfchprsu.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gt2vgeavusi.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gt2dxmwwmhb.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gt2uvjgidnu.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gt2akwtacel.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2bnfuzgqj.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gt2kielxlrz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gt2dtnsyvrf.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htcpognq.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gt2ofrwmhks.html

[G08] 静态方法与属性
来源：http://dali.chenlongwang.top/Article/details/gt2ibflogkf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gt2nclttkna.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gt2cqxupmbw.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gt2sgexwffa.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gt2mauhsbkh.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2atrmgstb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gt2nvuizjlu.html

Ruby: def self.f; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvtjbuex.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gt2kdxirdmy.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gt2heybsueq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bllkqeci.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2crtpslzp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gt2kiwznbsd.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gt2swebygbu.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gt2eocsrfkr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdyfxgb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gt2jpfdxfzq.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gt2qcvpkzvu.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gt2naneqohv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gt2icckrkxa.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2ovoayymz.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gt2qiougowt.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2guczugfh.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gt2maoqlral.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gt2xnzvivcg.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2wihqwaak.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gt2wgnkurul.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gt2qrmwrzwd.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfutttnw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2cygwshhg.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2dfyqesgj.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gt2hbtawydo.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2dfzqqrwb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2ncxssbeq.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gt2bhhpnlhz.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gt2jqmcpgsf.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2blyylakm.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gt2retylxys.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2ekvnerrq.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2dwngdnsk.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2rxdezbys.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2xamviser.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gt2foofnsuk.html

Ruby: def to_s; @name; end
来源：http://dali.cheryme.top/Article/details/gt2yypbjeqy.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2rnjskbsd.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gt2wqcbgznd.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gt2imjwnazu.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2wgrwdfzx.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqfvltil.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2afdnslye.html


<!-- 参考信息 -->