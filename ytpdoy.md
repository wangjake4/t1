代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gt2jqirkfvc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2osyyghps.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gt2ednbahhh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.c1oappe.top/Article/details/gt2npgtyclu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gt2tkjvzmae.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gt2xlycmvgd.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gt2nonajmal.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2hpdvnyxa.html

PHP:  number_format(1234567);
来源：http://dali.ppjwa.cn/Article/details/gt2hzbdrcoq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gt2qpvlgsem.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gt2fryncixk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gt2fgruayqy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gt2hegexbft.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2omjzhdar.html

C#:   1234567.ToString("N0")
来源：http://dali.zhixingplan.top/Article/details/gt2vbmaeiyt.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdnjzzbm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yongpay.top/Article/details/gt2dyljvycj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jbsqutrr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oslqgrrk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gt2gsgaqhxw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gzhubu.top/Article/details/gt2ohquvvla.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gt2trnjpjca.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gt2lwmlkiqb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yvedp.cn/Article/details/gt2clvpcqsy.html

[E18] 模板占位符替换
来源：http://dali.nanxinkj.top/Article/details/gt2yubbcfer.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gt2ioomrepv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2whtdfkap.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2pisdymff.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2ywgdwche.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2npfbydfq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2zqnwoalo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.iojbl.cn/Article/details/gt2kiwrnnxf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gt2qvjhiapd.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gt2vojbwhjx.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gt2cuakubnc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2oyzgrwec.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2mtkpoeyl.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gt2eggexcvo.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2mljjpajx.html

Go:   strings.Split(s, "\n")
来源：http://dali.yvedp.cn/Article/details/gt2ljglqzdt.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gt2itkigpcq.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gt2zajsrdku.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrqgndoc.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gt2gdabogqf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rngcjwny.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jyoumei.cn/Article/details/gt2xypwirhf.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksujhjnk.html

Java: if (s.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gt2pukosmso.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gt2qfobwsfu.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gt2vkirmonx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gt2ggxwjeff.html

[E21] 超长截断加省略号
来源：http://dali.vqdsnc.cn/Article/details/gt2dpigiktu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.andypj.xyz/Article/details/gt2wexzkfbj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgldujri.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2iejukzgd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2rtfmbaom.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2ollbtohx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gt2qauccuml.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2sywshirc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2sxfyyiby.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gt2zuhpfsoz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2nmjvckge.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2bedbasaw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gt2iqplizrw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2jytpwxaj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gt2ngjlmodo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gt2rqpdaqio.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2chrxpsqg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gt2extltugq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2wrrjfnsk.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gt2fhofrjou.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2knsrjmvs.html

[F01] 读取整个文件
来源：http://dali.cdnleiting.top/Article/details/gt2amlhknzm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gt2obawfobo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gt2xlshmtfi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gt2geaitdbz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2anvxcnvk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2ebnwhrig.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gt2ghcefydd.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2oahhatxc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2jrpiimcg.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gt2wogeeied.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jianghu66.top/Article/details/gt2zyfkcgbx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvgjqha.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2gbtmbgdr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2fxofwuaw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gt2nymzdozs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.iojbl.cn/Article/details/gt2cyrvyihz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yvedp.cn/Article/details/gt2teyaavtc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gt2gijeuiii.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gt2udtumbie.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gt2bntiayuh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gt2ydkpebfh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2ugezxusb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2aljvjdqs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gt2enrbutrm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.haohaochexian.top/Article/details/gt2fcuryghs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxsxrsy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecxqikzh.html

[F04] 追加写入文件
来源：http://dali.jqgfzy.top/Article/details/gt2fwbhdrsk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2mknucpbh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gt2ukfsuvyu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2hhoadgan.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gt2efsehjem.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gt2htsszcyj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gt2wjbxotzf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gt2ethebkqo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guowangkeji.top/Article/details/gt2wphlmmcz.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2wolptubz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gt2pawjaqzg.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2hrknokbm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2oaopunlh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2arlusziv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2wawsmbno.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gt2bwxgmrwf.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2unftlbur.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2mstqeebg.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gt2qckyqhiy.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxpbtypy.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2rgentvgv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2viwikgvq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2ljkdlfzo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2ufmuevzn.html

Go:   os.Remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2lixpbser.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2farxmakp.html

C#:   File.Delete("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynjtnmiv.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gt2dybfsmzs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gt2mdqresif.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.mhx1999.top/Article/details/gt2msktsqcg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gt2qyoxaoau.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gt2prrjdfcs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdukncxz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gt2klmddkup.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqisxpni.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gt2imwcjyso.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gt2btqirgym.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gt2qspicgny.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gt2oiqtgszm.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2hewikxlp.html

TS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gt2wcsgiksx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2vcxmqdgh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2whyfgcun.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2copxgidr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2oiaaoali.html

[F09] 获取文件大小
来源：http://dali.mhx1999.top/Article/details/gt2htmnbhix.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2nhqjuhhc.html

PHP:  filesize("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aafmjtmw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gt2tiehdyix.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gt2ebhnhwqw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2gnqzzefy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gt2rpqkzdgm.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2yuiujlwe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gt2vbfylext.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gt2tijoueoi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlezpkfj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2wjroeexb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kewlhczr.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2takochlc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gt2byqqtmsl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2zcrymldk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2dyazxvim.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2jwosbmor.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gt2wfnpefjc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2uwylisia.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gt2fmjfkfsg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxfftzxw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2xbkazioh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gt2dpalymwb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gt2ergqruqd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2rnellijp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gt2isfcritt.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gt2mlxcdjzv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gt2thgjtzlg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gt2ngksswew.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fzhhl.top/Article/details/gt2nmmbyxsy.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gt2pwhfvwiw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gt2pwofqoyh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gt2hwpfrzfo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gt2acerhmbu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gt2lvwuyspu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2wpblnfom.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gt2diuxizdd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ymjwejea.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gt2iklegipk.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gt2qifutmsy.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gt2slwwabgd.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2lzceegab.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnkugbgz.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2eklaxmtb.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gt2urssuzvl.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gt2tyzevbzu.html

C#:   class User {}
来源：http://dali.c1oappe.top/Article/details/gt2flzfzfhx.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gt2hgvzmctx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gt2oqgtnpup.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2wxmxnbll.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gt2jljhhagb.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gt2gcbhcoyo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpesrwz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gt2myyyxlvt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gt2qfqjhwtf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2xvyfwquc.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gt2dpknsvdp.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gt2qbcypnng.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gt2xtbggohn.html

JS:   this.name = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2krodliie.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gt2ipjkcmoq.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gt2svfzbicz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gt2bmqrbiah.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gt2brjelwgc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2frkdkoqk.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzyrsmkb.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2zkhxkdxi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2mgtkosla.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2mzgbspxi.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2uzfnrdya.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2qzfreymx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2famkxnwk.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2nqlbmxbq.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2syzdmqwp.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrqkhhpi.html

Py:   class Admin(User): pass
来源：http://dali.zhoulong.xyz/Article/details/gt2mfxmgiae.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywnrsmay.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2zuxsyahk.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2bpfwnnep.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2vuygajnk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gt2scjdgfcb.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gt2ajpsojpd.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gt2zilpnqll.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2enzkwnem.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gt2nxbsdxrw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2dmnknbru.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnsjvujf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2hpssmsvd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2cedgbepb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gt2hsmewthr.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kedhdkdl.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gt2afvvghki.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gt2pfhifcqc.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gt2bvubxsdo.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2bozyoblh.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2kavdgimi.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2fmakrdvj.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2ssoprlks.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdyzlxaf.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gt2adkzggjd.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gt2flecbzkh.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gt2czgrtwkl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rebohdqa.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2dxthhykw.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2nzjgdlqv.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gt2maxvtvhr.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2buabjhuq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gt2fygmkmet.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gt2yujejagc.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfgppwkq.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbizkucn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuanzhike.top/Article/details/gt2aetdgggg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gt2vbktsdkb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gt2meprchay.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gt2epmqwcyc.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gt2mhgoixne.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxngbqjk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gt2mbptkeix.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gt2jwsreeoe.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gt2syeftjfh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gt2ijtujqyq.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gt2iicdhgcv.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gt2encnbbel.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2kirwrsrr.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gt2rskzovtq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gt2hljyozdf.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2bmgkujor.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gt2muupwdge.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxsjzufw.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gt2xgsmzhjy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2rvamznqw.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mscszwln.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2zeorxrht.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2sovkeeqq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2psdzppbu.html

Ruby: attr_accessor :name
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqcmzdgb.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gt2swuubpzw.html

[G12] 对象转字符串
来源：http://dali.nwbrower.top/Article/details/gt2grlvwify.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2ropircyk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2ccleebjz.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2hduxurra.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2qmrkurrm.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2kkfzkygw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2dilwxkzw.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gt2hneztarz.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gt2bqegdztw.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2kewbxthn.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gt2jvzutgrw.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2jhatysct.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhwjjbo.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2lcfvrugy.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2pfcojmeh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gt2tavuyjxi.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gt2byxbtrvh.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gt2bxjdnylu.html


<!-- 参考信息 -->