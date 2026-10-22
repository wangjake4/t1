代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gt2btnntjrr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.redwolf501.top/Article/details/gt2penkbtrr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhoulong.xyz/Article/details/gt2rgfvfqmq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ybcxt.top/Article/details/gt2jkqcrumh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gt2aexcsbbg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gt2kgvvvxin.html

[E16] 数字千分位
来源：http://dali.hfpthk.cn/Article/details/gt2yxghuubj.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwrbytpz.html

PHP:  number_format(1234567);
来源：http://dali.snrcjt.cn/Article/details/gt2smmrcsks.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gt2azxbawls.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gt2gmccalcx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gt2cniyexzb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gt2vjllumji.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yvedp.cn/Article/details/gt2ygadnvvx.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgaghsmm.html

[E17] 首字母大写
来源：http://dali.shzxlz.cn/Article/details/gt2bpiijctn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qmgzbftm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.snrcjt.cn/Article/details/gt2hpeppsgg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gt2jtccmawq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gt2ymphsllj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gzhubu.top/Article/details/gt2hpmfliot.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gt2zporpnoi.html

Ruby: s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzzkjcrk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenlongwang.top/Article/details/gt2ojlgwpmt.html

[E18] 模板占位符替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rronoqpq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aibaodan.cn/Article/details/gt2aafqttax.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gt2nmrjllmb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2nqfkgart.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2dtejclrc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2spnugyzr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdsaejwz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gt2jqmpnnun.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gt2prbkleir.html

[E19] 多行文本按行拆分
来源：http://dali.gzhubu.top/Article/details/gt2qbooghjg.html

Py:   s.splitlines()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibxlfomw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2easrjdlo.html

JS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gt2inppnkuj.html

TS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkuomylg.html

Java: s.lines().toList()
来源：http://dali.c1oappe.top/Article/details/gt2ihtaihks.html

Go:   strings.Split(s, "\n")
来源：http://dali.hysaishi.cn/Article/details/gt2lhobyabe.html

Ruby: s.lines
来源：http://dali.zhongyouzk.top/Article/details/gt2pveorgbb.html

C#:   s.Split('\n')
来源：http://dali.ydzc1.top/Article/details/gt2tdkkcfsa.html

[E20] 判断字符串是否为空
来源：http://dali.shuidangran.top/Article/details/gt2aluploph.html

Py:   if not s:
来源：http://dali.gzhubu.top/Article/details/gt2jdwqcwsu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gt2qfqpjwfq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gt2jkorpwqa.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gt2oahapdwd.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gt2lwqlvqyn.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gt2rzekzlpu.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gt2ljppcqwl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2netafgoy.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwparblf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gt2pbrkfrln.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2jxdtrrua.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2fvsykeya.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2lascyzoo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2hborqfyi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gt2bfuanthb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2ovgzydtx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2ciydppzg.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gt2firysjfm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gt2umekobuu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bljstasm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gt2dnjteunn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gt2kqioysib.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gt2tbqdrvni.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fzhhl.top/Article/details/gt2ucwspvmq.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gt2aecwnmgv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zycfv.cn/Article/details/gt2qoeexnnp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2xhganexk.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bttfliav.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2qcmxslpb.html

[F01] 读取整个文件
来源：http://dali.yj20258.top/Article/details/gt2jmnldfwx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gt2taozjcpt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwembvhh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guannengcc.top/Article/details/gt2shygukef.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2zvtocfxa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2viqnlpxh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gt2lltbxvff.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2izewcfds.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2otmahomd.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2fnpmpbht.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxirufed.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gt2snbhfian.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2amigixwy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gt2hrthtaoe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2ilqnsnwf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gt2tzpbctbu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gt2gzwvvafc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2holqymgq.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyeyfif.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cheryme.top/Article/details/gt2hhzckuil.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gt2gnwcyesz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2aotrcetk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2xwbzjyrm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fzhhl.top/Article/details/gt2yvzdrzxb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gt2fldmzlsu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2meusudse.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gt2sayoikad.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gt2ikiotezd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gt2nrtfodcc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhwpzhvt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gt2gurvflph.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gt2mlsthhzs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gt2bbfwanbb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2wahhormq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gt2plejykpi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigufen.top/Article/details/gt2alkdcrdc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfkieuky.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gt2sywlmbbv.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2ycxrwmps.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2azgxciyx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2tpkdrwol.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gt2htgxeqco.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvtrcpdn.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2ekiocdmk.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2wimkfzck.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gt2eduvjxll.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2jutntwmj.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2bnpfktkt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2tdobcpam.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2kngntpvu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hquacpwx.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2vkenpmpm.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2dbywwgrc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvahuyvi.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gt2ngoyqyco.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gt2wofxfkxi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnqzz.top/Article/details/gt2lynuqhle.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gt2xqjpkyil.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gt2peejzihf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gt2isgvvonr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gt2yieifohx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gt2grtiuiqp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gt2mraqtqnc.html

[F08] 遍历目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2lfcrmdir.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gt2ltscyfnk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ymdgrkxc.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gt2zisyogie.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2tftpzosh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gt2noiconda.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2rzkrqiya.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2lwkxyawy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gt2sgmmyudq.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gt2dnroqbii.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ezeikpnj.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2gxojpkzs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gt2hqzpnwue.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebftxyfa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2bwkjkewu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gt2onjkkttf.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2mdeusikp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gt2umgvquus.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gt2ooqejbrv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2wbisoayv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2kiadlbuf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzwyhsqj.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2cxtbmlki.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gt2bwfjjxco.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixxcevvo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2myfmyovq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fskoyyyg.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gt2ywjwgatt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2isqdylif.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gt2fejjuqty.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2oeshbypt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2reedzpvr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gt2wgtlsjlz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkdstlvs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2xiejhges.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gt2suldixop.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gt2bnewnccl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fzhhl.top/Article/details/gt2kldfxhzp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gt2jdxtgrcx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gt2anpzyzfr.html

TS:   // 同上
来源：http://dali.wangdashe.top/Article/details/gt2citsdsvs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gt2bhnnszvj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gt2nkiyhfwc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gt2ofxvskoc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgufenzy.top/Article/details/gt2ngbwsdwe.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2qmrmmucp.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gt2aupcrnlx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwsyscnw.html

[G01] 定义类
来源：http://dali.aizwys.cn/Article/details/gt2sjutbanq.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gt2byafsohf.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2achudrhe.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2rwiizphl.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gt2sgzpixht.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ifbmkjkh.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gt2frbgaqiv.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2glcskcqt.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2rzppitbf.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gt2hgqzvukm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gt2grdrwvyx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gt2hlglczum.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2fjyexinx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkwtglgp.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2pystjopc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjgaashf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2chueuaql.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ghvgaqkd.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gt2uszuamay.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2suedftde.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2lytfvuld.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gt2vbdnnlzu.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2igdvgwjt.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gt2rrndipmm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gt2waqopmpw.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gt2tfewwuzn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gt2hyaisqzk.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrbmvnml.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2dfchljvv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gt2cwtzprcv.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2jaobvfgr.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smltimwo.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2mzulgkkg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2gzjpkmoc.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2ixqhunoj.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gt2lflxyidk.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gt2ilukprny.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gt2pokxhwja.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2rjbbzwrp.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2jdsfaaka.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2iqnxmyzc.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2wzslkqup.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gzhubu.top/Article/details/gt2lveivttk.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgeihmxh.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gt2ivpbrvcu.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gt2hjrisfpw.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gt2psltgdww.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzsybzii.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2vzagovtv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2odievrai.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2wtlhbkkd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gt2wtmjrfqj.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqmicnrj.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gt2bipifuwr.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gt2lhzvrbit.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gt2vdrgidgy.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gt2nvjxjlcx.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvfekqic.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2vciamsew.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2ydaquayx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqvtxjjt.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gt2momueznr.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gt2xgsctndo.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gt2rjodzojg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gt2lzvldqag.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2rkhguxkg.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gt2mytwteee.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gt2ijjuhawp.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkvcrder.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gt2ltqclryp.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gt2ascclshh.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gt2clstgbfv.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gt2eshkvnmx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gt2sgenkprw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gt2sybzdqqj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gt2stkghmfh.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gt2fnqgyyzj.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2bnpgjbrl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gt2fwnucdve.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwppaoeq.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2kljtsuej.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gt2iceaimng.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gt2rnxqgudq.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2swxpnxuj.html

JS:   #private 字段；其余公开
来源：http://dali.fengsongda.top/Article/details/gt2vimbbgvc.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2avrxxkgq.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gt2ocfvfesc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gt2sjcrpxax.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2asklvlof.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gt2feiwygnr.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gt2wbffoojt.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gt2fhhukwgm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2urqbuqog.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gt2dciwkuve.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fwnsszcb.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2srtxecqy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2tmtlglnc.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gt2ftzwtyfy.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmaqrlwl.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gt2czuokqwn.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gt2lnlkiohd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2oskdbkjr.html

JS:   toString() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2tuncfqqb.html

TS:   toString(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2nvspdlak.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2uiwwvitg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2fubpvqqg.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2bkxecggr.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gt2rgwuskwn.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gt2jezsghbh.html

Py:   isinstance(u, User)
来源：http://dali.yvedp.cn/Article/details/gt2fqqkxvaw.html

PHP:  $u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqdzfcgj.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2ekgxrdws.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2xfeqawae.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2onaiyckp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rnzewvwd.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gt2osrrsila.html

C#:   u is User
来源：http://dali.ybcxt.top/Article/details/gt2mretzctk.html


<!-- 参考信息 -->