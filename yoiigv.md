代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gt2mrehluoi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2kvzqyngh.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gt2wykxxnuf.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gt2oasowquy.html

PHP:  number_format(1234567);
来源：http://dali.yj20258888.top/Article/details/gt2qoqwtdmn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gt2iivoasds.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gt2ewefnbqx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gt2mqpdywit.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2olpsguhy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gt2soqgaavi.html

C#:   1234567.ToString("N0")
来源：http://dali.meibo888.top/Article/details/gt2skvxndhy.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gt2nmjoyhzu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.mhx1999.top/Article/details/gt2nghkuloa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cucudq.cn/Article/details/gt2mthvevva.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gt2myopioep.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvojbyy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idkytijy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xinyue.icu/Article/details/gt2edtrfieh.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gt2bjjwtwft.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gt2dyaposxy.html

[E18] 模板占位符替换
来源：http://dali.hywenlv.cn/Article/details/gt2bvblvfos.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xdggmomd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhongyouzk.top/Article/details/gt2iaoochft.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2iqkuvpdm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fywrtaxu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2nzyyemkf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2rlnddfwz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gt2npolufns.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gt2vrhusvmw.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gt2fytocikc.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gt2hpdlqfvf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2bxyxtsjl.html

JS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzgsbytd.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gt2pktslgge.html

Java: s.lines().toList()
来源：http://dali.havefunace.top/Article/details/gt2jcabaszs.html

Go:   strings.Split(s, "\n")
来源：http://dali.yangfankeji.com/Article/details/gt2icbtgzss.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gt2kngseuat.html

C#:   s.Split('\n')
来源：http://dali.pycfn.com/Article/details/gt2xsegrshv.html

[E20] 判断字符串是否为空
来源：http://dali.havefunace.top/Article/details/gt2cifsehqg.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gt2oayvddnz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gt2uvzdlvee.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gt2zajhbxzh.html

TS:   if (s === "") {}
来源：http://dali.ppjwa.cn/Article/details/gt2wifahsgf.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gt2ognmcett.html

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gt2igdofuet.html

Ruby: if s.empty?
来源：http://dali.yj20258888.top/Article/details/gt2yslhrfhz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2vnwxiemq.html

[E21] 超长截断加省略号
来源：http://dali.birdmap.top/Article/details/gt2ksaazyjn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gt2akvpdjvo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2rcvyxixj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2dhzfnymu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nxwrdqnv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2zlfktjny.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gt2kyblnkgv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2subpzqyi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2plqscinx.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gt2kikrtgcv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gt2tjvaxdyz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2rcnpcysb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2nnlgzvyf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2cxusgbbs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuxming.cn/Article/details/gt2ztreldik.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.vqdsnc.cn/Article/details/gt2yqwkrlar.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2htdiurlh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gt2bwgadipx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2zvckkdlc.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxslaltg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2wxuupium.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmhujmdr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gt2zqveqfto.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2clllgcxn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gt2muvoouzm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gt2csyyvrji.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2jtdbonfs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gt2slbsryho.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2oiaissds.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2splscckb.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gt2oujcuzzp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gt2whmvfwzq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgfzy.top/Article/details/gt2fbabzroc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gt2dvbbfewo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kltekyfx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gt2czyrsqns.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.smart0.xyz/Article/details/gt2stdsunho.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sxryk.cn/Article/details/gt2bwvasjjc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2znohgnul.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gt2xkmpjxib.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2hwycsuia.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlcxxrce.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2cvxutoam.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2nhrtdwew.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2ehiawxuz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gt2hrdkshpq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2pnlzkriq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gt2dgdmewcf.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gt2mleqnrey.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvusnmtl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zycfv.cn/Article/details/gt2wqwytave.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gt2mcmqtzxt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlbvzhvp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gt2opdrifzu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2yuzczrqk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.kuanghao11.cn/Article/details/gt2wtgudvae.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gt2qevucnob.html

[F05] 判断文件或目录是否存在
来源：http://dali.aibaodan.cn/Article/details/gt2ycdqfuiw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gt2hrtqjmpu.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2luevzfch.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2acmroteo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2vlaubylq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2ylqexfne.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gt2dyuxfogs.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqsslqfg.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2ojtwglbu.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxydzwcp.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgmlqmqo.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2lvecdozp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cetfbasi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2elqyvyvy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2zgrcrnwc.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2hbgqonuv.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2dloxzwum.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2fvfhuoeq.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gt2fyphpyga.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gt2voicgprn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gt2gqpjacgk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gt2hkvidpar.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gt2ritaoucd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gt2ldhicndc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gt2inktxchs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.feifeiyinyue.top/Article/details/gt2itzbwosj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gt2bpshngwm.html

[F08] 遍历目录
来源：http://dali.shzxlz.cn/Article/details/gt2wuzcidhh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gt2jcdunsly.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gt2vskgofxv.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijgrzsub.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gt2mokggwaa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2cvjvbhxn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gt2bhprsakg.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gt2ajgegtxe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gt2knaangxo.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gt2itrilefa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2aajhahpz.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2cmcxazms.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gt2edkhkhms.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gt2jnpxmigo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2psncovwo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gt2xobpntyv.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2mdnuybvj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gt2hszigwyn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gt2iozpsfpc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2taalgfgq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2xnxntnsz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2xratfoxk.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2glqwtfme.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvevddrf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ouwxfjoq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvdctask.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2eccvixaq.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gt2ttwvfnwh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vukvuopp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gt2johoxftx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2lfhhlgnt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2ifpmbwid.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gt2rjwyyaje.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gt2lbxcvnnz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2nmouzzsc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gt2ekmucxoy.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gt2nvbagacg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gt2ubcaepku.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gt2vhaiuelk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gt2eknznskj.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gt2ldhusiib.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gt2goimjzee.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2aaeyydgx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gt2upecacir.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gt2ufhjredd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2krvumnlj.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gt2sgujywzr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2hdhtqnyz.html

[G01] 定义类
来源：http://dali.dianchejie.cn/Article/details/gt2kgmldihk.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tordapla.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phhdlpvj.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2uyxbrtpu.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gt2rdtxzgcu.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gt2yvelknxu.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gt2xfqyyckz.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gt2shrnjwxk.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2zxrkudnq.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gt2neriosln.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gt2cytphkcv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2iccazblm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2aoirvdko.html

TS:   constructor(public name: string) {}
来源：http://dali.xziqi.cn/Article/details/gt2cslvptsh.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2abkfwgqz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gt2bmpfzdxf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gt2mloyxwud.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2jtshsibz.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gt2oogftqvn.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhbrphgr.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gt2vmrjxtgs.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gt2fmvyuyys.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2zchkjsrx.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gt2kehlqwul.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sysykeji.top/Article/details/gt2kehjpilk.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2jbyjylxk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2ndblfzlo.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gt2rjtjxwai.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2qxafpigb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2dbwxiclj.html

JS:   greet() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2qxapsulp.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwqajccr.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2rnnktyrz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2hoirllhc.html

Ruby: def greet; @name; end
来源：http://dali.mhx1999.top/Article/details/gt2bidfzipt.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2vdtimdbp.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gt2pfrnntzd.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gt2sgzzovbk.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2rqggkxcs.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2jxstalbz.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2amuzmari.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2etrjojsb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gt2cdfxwibn.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gt2qevdtnix.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gt2uutuylni.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbxelzvn.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gt2tvkegdwk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2uigxqkyc.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2xbswblbr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2zmqmdfwi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2pwgtkgcm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtohtrnu.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gt2opstpeze.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gt2ilkqwgcu.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gt2eflntjte.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gt2sjuilavr.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2qsphzkfv.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gt2xkxfdkap.html

TS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2abbsosuy.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2vgqhjgxf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gt2ewgjkzpm.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvvowpkp.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gt2ydjuyobj.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gt2zyderdsv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wifgfbkz.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2sohlkuof.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2asnhwtki.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gt2pagkzemy.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2hsalqbdo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gt2dyzbnihp.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gt2knxyhvew.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gt2rskdttzg.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gt2qsqjsfiv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gt2jxpzxlpr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gt2ciisxofw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gt2szbnzhgs.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gt2behgmklh.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2mhtswftw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gt2fmntazeh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gt2nfakxyah.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrpecmc.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gt2acajnpsl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gt2bylpruee.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2yjgnaqwl.html

JS:   #private 字段；其余公开
来源：http://dali.jyoumei.cn/Article/details/gt2nvxqmfjn.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2jilodkei.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gt2ntkeywhq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gt2onhfqazv.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2xfyeuxox.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gt2dprzbvqd.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gt2arnvqyka.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gt2xajrervg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2owxdcjjv.html

JS:   get name() { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gt2rjtncqog.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gt2pzdsojid.html

Java: public String getName() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oeycbdzk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2deugqlwm.html

Ruby: attr_accessor :name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdnsrwih.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gt2lylaqhde.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gt2fljmvzjf.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gt2enpuonhm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2zbndgfhc.html

JS:   toString() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2fsxvuovp.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2aytcnppg.html

Java: @Override public String toString() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2nggrlsnl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cpeuimpi.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gt2zliwzuyo.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lyqhbblr.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gt2vscsivix.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gt2cejwpnvl.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akhhvonm.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2xgrbfdcb.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpvphpqq.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2ezijwwiw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gt2jznqcjyr.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gt2facnrorh.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gt2igheubdn.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gt2zsbkufyp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gt2trneaapf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvdcnunw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnsabjle.html


<!-- 参考信息 -->