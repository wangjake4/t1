代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gt2cofvnahm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gt2yjtoxnds.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gloqcxuc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gt2pskmfezn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2stxtseez.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.smart0.xyz/Article/details/gt2thyhcovh.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gt2yuujzleo.html

[E17] 首字母大写
来源：http://dali.jianghu66.top/Article/details/gt2inhcgppw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgfzy.top/Article/details/gt2ikxssthf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gt2sbbyvnan.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gt2vmoggczd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gt2fnniritb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nlqykrxi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gt2disboxgl.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gt2cemwbtbb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gt2rctnywkb.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gt2pjttaztx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxinkj.top/Article/details/gt2wowvmgfr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlvhaool.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2kzjrovag.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kayhfuyz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2dwcgtmdz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2bhgsubmd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gt2ffalamvw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.havefunace.top/Article/details/gt2qyhmmceh.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gt2jjfdlexh.html

Py:   s.splitlines()
来源：http://dali.hammf.cn/Article/details/gt2tritvxom.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2zmnoxyag.html

JS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkqjhyfx.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gt2gtamiyul.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evugzigi.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gt2qizsxvrj.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gt2vxdlcbab.html

C#:   s.Split('\n')
来源：http://dali.xylfe.cn/Article/details/gt2vaxsmxcl.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gt2ovygamdw.html

Py:   if not s:
来源：http://dali.yueranfly.top/Article/details/gt2svwbdzel.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gt2wouewtxv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dashuyun.cn/Article/details/gt2reveqaob.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxrolkg.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gt2mdgdazlo.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gt2xivughog.html

Ruby: if s.empty?
来源：http://dali.bjfxy.top/Article/details/gt2neaqjxud.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gt2ejglqzdo.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gt2fphdpthn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gt2khjsdktp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2enspdlio.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2ivjifeva.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ribtgfjd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2vnxlkclp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gt2gsgugegf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2tkohvbvw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2ogwpslfi.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gt2frfdevmk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gt2liqkmyoq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2uxutjfja.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gt2kocvylya.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2fendqwlj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ybcxt.top/Article/details/gt2qvapsiwz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gt2fcfolnov.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knzyjlnj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.iojbl.cn/Article/details/gt2mxrfalvd.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2lxqfjkvm.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gt2celdnecn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2glcqmfty.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gt2hbjqwxsh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gt2ropwudpt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2gasbnfio.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hysaishi.cn/Article/details/gt2rrqmziko.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2nwmnowxs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gt2wyyvmcqi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gt2hphzrzih.html

Ruby: File.read("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2zlpwncmh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2bwbtrmtb.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gt2vfigteqg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gt2lcwezoeg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenzaomai.com/Article/details/gt2qctwfpki.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gt2dyxkrbui.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gt2nubehdsi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gt2ukphoffq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsotfxvi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2srzdxver.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gt2rjprmhup.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gt2iksrktat.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gt2wrjjywjw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2qcnjilci.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gt2ajgnwtju.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2pkjhxjev.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gt2nkwtibiw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.9152youxi.cn/Article/details/gt2jxgxrxkx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2byygtfuz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gt2cppigfnm.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gt2azfrzbob.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2jigpkudl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gt2jufuiple.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gt2jkeugiyz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2uijqotcp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbznlwmm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2cdsnhktk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gt2vaadpgla.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gt2uhamwafz.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2ynsuorfh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenjidiqi.icu/Article/details/gt2idouzgqu.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2edyxotpb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2ktslgrld.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2dwqxwgpq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2wwqivcie.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gt2usldsegn.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvphjnvq.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwlorlmo.html

[F06] 删除文件
来源：http://dali.zhengqikj.top/Article/details/gt2krmmedvo.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2welmgdul.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2renrfcjl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2hvfvbbge.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2wuspmprj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2yhuwnzti.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ptqurcau.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2sjpennhe.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2hmbdekkb.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gt2tddhjmtq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ieglnlse.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gt2buofvztm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fvwlazbd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fekjxokq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gt2xwuvulft.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gt2jxggwujo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gt2kxaoxhhk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gt2zsqvotas.html

[F08] 遍历目录
来源：http://dali.daria6918.cn/Article/details/gt2eycvthgj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gt2rejzmuqu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gt2rpuefgxi.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2nthdbnmj.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gt2eodirgde.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nitgcntn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sweek.top/Article/details/gt2dgxqhznq.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gt2ucchpsxy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2fcuemwfg.html

[F09] 获取文件大小
来源：http://dali.yj20258.top/Article/details/gt2xksipwyk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2teprofzl.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2suytqzvh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gt2vmxmgrsk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gt2kscgcouj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2kcqyrzjn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gt2nxlkymae.html

Ruby: File.size("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cskycwei.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gt2nfjuvhnm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gt2vsovnlcb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2fgxfbanf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dslhruyd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2timfoqph.html

TS:   path.extname("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2koffpqog.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gt2gqnjamed.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2hzosfqsh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2hafxfxqb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2fegglzau.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gt2enezqljz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2snpvhyfl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gt2sawupbkn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2ztdmcxks.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2kwznjeuu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ppjwa.cn/Article/details/gt2twmdgjwf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2xdugxxbl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2vfcxcbrx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfbxevcr.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gt2hbqxxias.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gt2jcldzygp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gt2oplnwrql.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gt2olgcnsqu.html

TS:   // 同上
来源：http://dali.vqdsnc.cn/Article/details/gt2xzkpxmty.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shangyingyoupin.top/Article/details/gt2piuoxuwm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gt2vuzqswsz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gt2ermvajnq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gt2jxoelpfl.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2hdrztmvn.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gt2tthborgo.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2drbxvbzh.html

[G01] 定义类
来源：http://dali.jyoumei.cn/Article/details/gt2nzbutpuj.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gt2rxqzhekh.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gt2tjmsdcwn.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2lhzjxgic.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gt2yuevwapy.html

Java: class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2msuxpept.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gt2rjyeepgu.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gt2qvuxdpsu.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2luqsbnpu.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gt2jdpvxsgd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gt2tmazmtjo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gt2fmdzvwka.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2ohbisuec.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gt2uyclbfzk.html

Java: User(String name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2zsadbkxj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfmogtcl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gt2effplrgs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gt2lkjigkib.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gt2cyxdswht.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gt2znjgkdxj.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvteyxdt.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2ykdljiiz.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gt2jekemdgx.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gt2kqftgpwc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cucudq.cn/Article/details/gt2kqccnzoi.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxgeshkh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2uvobsdxm.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gt2bysomoem.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gt2eqbputrx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2doruvkpe.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2oqhffchg.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2vowtdauy.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2bwuygkzh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gt2gtldafod.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gt2safdzsla.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gt2wdmcohcr.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gt2rujgcrbm.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gt2noanxwno.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2hhiwoofa.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2myuqujsb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrogrbw.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2ypnqezwr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2ysclockb.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gt2cnkbolpb.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gt2zrnozlzf.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gt2qtymecud.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gt2tufcuhdy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2howlorpc.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2vhsotqji.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2pjxuqxhn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2ufswimzs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gt2ztastovv.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gt2xxuiwbrq.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gt2krjaugjn.html

[G07] 调用父类方法
来源：http://dali.nanxuanxn.top/Article/details/gt2gmaqunob.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gt2fvtzbxmf.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2wzjzedqf.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2oqfnruac.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2ydiccjrf.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gt2tcdefzus.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2vuqbsflz.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gt2wdmthpra.html

C#:   base.Greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bibfqjxu.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eaulgplu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gt2tizhoond.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gt2pskciyod.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2osmikwlf.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gt2ciczknab.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2veeujngq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gt2zlmibahr.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gt2ovwiexsy.html

C#:   public static void F() {}
来源：http://dali.snrcjt.cn/Article/details/gt2urwblxtz.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gt2fvhrnjet.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gt2rdpsjvku.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gt2qwrmyswo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfsxynos.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gt2lifbubzl.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gt2ihtmdymr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gt2gfwscdax.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gt2tvtmrwls.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2favlgbif.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gt2zrrarnsq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gt2jvdtnont.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2rwlqsahc.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gt2dfnkvysa.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2pnjpojpw.html

Java: public / protected / private / 默认包级
来源：http://dali.316326.xyz/Article/details/gt2lfkawnpi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gt2yhnosgjn.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2ovwiihix.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gt2omhzkcra.html

[G11] getter / setter
来源：http://dali.zycfv.cn/Article/details/gt2eykcoxps.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gt2vbstpjah.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2nvaenini.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2yfndgkap.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gt2whuqdjho.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2nvvclafe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2jowgzgrh.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gt2ciuyfexl.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gt2ifrcwxtv.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2abnywglq.html

Py:   def __str__(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gt2wsjonmnc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2nqryevmd.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2bwcghdot.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2lnodwtke.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2eummcsnu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2jivrdthq.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gt2fommkubo.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gt2hzrsqniv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvsilej.html

Py:   isinstance(u, User)
来源：http://dali.zhongyouzk.top/Article/details/gt2vitpvoan.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2mzjgesca.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2dgnqklxe.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2pfibhhid.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2fudbgrce.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gt2fekdcvtl.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gt2hpiindjo.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gt2huecyncw.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gt2tfjbxtoj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrunbcmr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gt2ujhkylpk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gt2qhvlgwnv.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gt2orezufcq.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2dnabyyhz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gt2iykkjrdh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gt2pityhffm.html


<!-- 参考信息 -->