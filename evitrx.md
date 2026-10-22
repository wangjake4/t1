代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ivvv.top/Article/details/gt2ryriopuu.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjegjsk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vrkhasca.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gt2bpjrknso.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2qktviupv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gt2kneliwsy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuanzhike.top/Article/details/gt2pcoppdim.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gt2mhutwvou.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gogol.net.cn/Article/details/gt2zjlrcurr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gt2xbzucluu.html

[E16] 数字千分位
来源：http://dali.hnqzz.top/Article/details/gt2qhgxbsyr.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gt2vatpzejz.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gt2efitrisk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gt2mopucgcr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gt2glfiwjsq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2wjeebwtc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gt2zynwrimd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gt2iybeyrzm.html

C#:   1234567.ToString("N0")
来源：http://dali.jiagoushi.top/Article/details/gt2oqcplcjo.html

[E17] 首字母大写
来源：http://dali.hongshengwenyu.top/Article/details/gt2yevoxgfw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gt2hscbyphz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrxwfir.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2oqrtkxff.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gt2nvgmydfz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hammf.cn/Article/details/gt2qntatfmr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2byngalke.html

Ruby: s.capitalize
来源：http://dali.nanxuanxn.top/Article/details/gt2ysxktcfe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tian-w.cn/Article/details/gt2gxppatti.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gt2tayrwcvo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gt2wcelmryc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gt2tlyprexn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2bkzqpzua.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2fwmtemlk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhgunyvh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxkibeux.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqtwqlij.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gt2azijgjxi.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gt2zqpvtmwi.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhzrcnmy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2lyscrbch.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2zysqwopo.html

TS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nyizdwxs.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2xtqddojv.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gt2gwgkuyap.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gt2rkvdlvxh.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2dwveyvkp.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxvfumsn.html

Py:   if not s:
来源：http://dali.dashuyun.cn/Article/details/gt2jstemfkj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gt2vfnnqcoy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2isvyveyz.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gt2yiexcrar.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gt2xbfkihcn.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gt2fuiosdxc.html

Ruby: if s.empty?
来源：http://dali.tian-w.cn/Article/details/gt2viixymdp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2micoxovo.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gt2logndiod.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gt2ekgcfdlw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmnquzak.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njockedr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2vgduwkzl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2awejqgqq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gt2kjewdtrk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2zphskzdz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2ljrzmwsv.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gt2xnrngcyl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gt2nmzsmsho.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2urhmcswr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2crwsxekv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gt2jphiucsv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hysaishi.cn/Article/details/gt2mwaoxjel.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gt2jznbjodn.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcajgepv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gt2oerlvxde.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2yxtmyvcl.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gt2qpmofnnm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2zsiffvrv.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gt2tfccbmbt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gt2ypveihvi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2kgawrvpo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gt2wfzhpjgz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2smkciacy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2iokrcfej.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.316326.xyz/Article/details/gt2ipgutoiw.html

Ruby: File.read("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2trkisgpn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2hrjoegjh.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2jsvkwclk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gt2srmganlx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gt2wmnftwhr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2imafjtif.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2abluhxre.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gt2kjifvuzw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksnhaybi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gt2zuzrwenr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gt2fmgfvxtc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gt2kspsgkhc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gt2nrqsdswt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2uswtrxfj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmsxezlk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2dvocewdn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gt2bsbhmulu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mdslzxpt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gt2phthvbeh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gt2coetbecl.html

[F04] 追加写入文件
来源：http://dali.ydzc1.top/Article/details/gt2kxjwytqw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2azzzxvwk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuxming.cn/Article/details/gt2kjicylza.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2angkfkpd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2krenuffd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gt2eashobuy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2knczodav.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omhspbtm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.havefunace.top/Article/details/gt2scuogtqr.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2xuaaxwae.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gt2vpnqppbd.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2jxsjryin.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2vqnvhflc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2oyegqfds.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2ezckdlnj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenlongwang.top/Article/details/gt2rujuioid.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2befaazta.html

C#:   File.Exists("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2ylhidebw.html

[F06] 删除文件
来源：http://dali.jyoumei.cn/Article/details/gt2gmefgrkr.html

Py:   os.remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2llhtvffj.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gt2nnlacgep.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2fyntkgne.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2osldtxkb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2kayovixo.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2znrgkslx.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzaobwpw.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2fgjthtcm.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dyrribkv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pclfdfmj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqcsylib.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdjuisot.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2hauscuhi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gt2fiazduld.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gogol.net.cn/Article/details/gt2llpckose.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gt2cazdrifg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gt2xggfabmn.html

[F08] 遍历目录
来源：http://dali.shzxlz.cn/Article/details/gt2sulrdxug.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gt2kxahhyep.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gt2xvpfadad.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zaxqlhyt.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gt2jrxsfpsg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2erfjeblf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2ssvbpaqu.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gt2lulwbexg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.redwolf501.top/Article/details/gt2uqmddnex.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gt2wsalpwri.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2kzrkixoz.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2fwqztatb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gt2nhwgtpbt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gt2fcwmauwj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2snwixpha.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gt2iczyawpc.html

Ruby: File.size("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2ipejzjwe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gt2xnmauknm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gt2tphafauz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2dekqnyrn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2mpaigzbg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2rqpbqgis.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2doutdlho.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lofugrsd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2cnlrpgdn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2tjcbycsa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2eiettrxi.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gt2ygmknziv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2yypcakdi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gt2ovekogzl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2wyclmelq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2cubossps.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gt2tymzafko.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gt2encqwmyf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2ehllnzzo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.9152youxi.cn/Article/details/gt2hwgsaexs.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gt2yaakztav.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gt2wuiwudbs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gt2jrjcshab.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gt2puohfppy.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gt2rnomvrsl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gt2dagwdmes.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkdgvsln.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gt2aorygjif.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gt2xgifchkm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzcyvtff.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gt2vkkzdcbv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ijxrdwjk.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jiscewgx.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gt2dgdmpkkx.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gt2pleczwtx.html

JS:   class User {}
来源：http://dali.meibo888.top/Article/details/gt2hoalpocn.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edpzxmri.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gt2lzgucovq.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gt2jguduxbt.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gt2srmbnybw.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gt2tozdywij.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2ibgbphwv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gt2lnxkkgcu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gt2hdtjssfm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2fpxvfypo.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2grqmxxnm.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2betjjfvk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gt2blbrvpnt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2pudlmpec.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2ozqwldma.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2utygfjbw.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gt2ionxcvhl.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gt2msuqarnk.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2pbdgpktq.html

TS:   name: string = "x";
来源：http://dali.316326.xyz/Article/details/gt2rgchbwdj.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gt2asohcumi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gt2tcgpdkxw.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2luyszgbk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2yghxzump.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gt2ixjdmnec.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gt2vkvmwews.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2xoxrsshz.html

JS:   greet() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2tmpzjyno.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjuebiqf.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2fkoqzksh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzhmpwwx.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysnnqycl.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gt2embedbvm.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rlyqnqyy.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gt2iunppwub.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2pxtvbewq.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2yixmjonk.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2fkenutxc.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wtqqrkuo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gt2wqvdpxju.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gt2kcitnlsc.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2azjhiuab.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gt2xviefzgj.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sphomegv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2hnxgynoi.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gekikkmh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2fpbtzrcn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2bwpohrxk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gt2xbdjfvsy.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gt2iobxrcsj.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gt2hbnvvebd.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gt2atsmiajn.html

Py:   super().greet()
来源：http://dali.jyoumei.cn/Article/details/gt2avgikwxq.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gt2glredsuk.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gt2lfjunjgk.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2ubqdzykr.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gt2fdkbghyt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gt2ngnfqhcj.html

Ruby: super
来源：http://dali.tianlin.xyz/Article/details/gt2wqzheqkt.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qivfygfb.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gt2dkdenoge.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2zefkhcxb.html

PHP:  public static function f() {}
来源：http://dali.ydzc1.top/Article/details/gt2yrlujdgz.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gt2byxzuoiy.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxdagase.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gt2htcggimm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gt2lhnmqxar.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gt2rowgxnce.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrzsrbis.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gt2nxhbxgkt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gt2bvgixemk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gt2iadyeuud.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gt2gluqmwzp.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gt2mhstivhw.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2iyvcqydu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gt2exfwhuyh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gt2bawigndf.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gt2gasjjezk.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gt2txkmbpsd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gt2lpddohpq.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2hotadwfr.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gt2zhrpbzzq.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2cfqsybgk.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gt2lnhfhyoi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gt2jdvvvubd.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rabkrzlm.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gt2irsdohcf.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gt2jzadazcu.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gt2ppieiumn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2omcvyxxr.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gt2abfyizso.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gt2dwfnvywh.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2mgvqnhul.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2dokyrahl.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gt2chdtdmbf.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gt2ajvrldep.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gt2akdqncef.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gt2gvjiegcc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2fsycmdmj.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2rmpscmrf.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2eyxauavq.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2pthjhhwt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2kooiprui.html

Ruby: def to_s; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2nrjequnn.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gt2bthafyjj.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlmhsxyq.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gt2pogdntar.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2knltwmqu.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2liuftpyg.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2dmazcpzs.html


<!-- 参考信息 -->