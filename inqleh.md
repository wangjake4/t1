代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gt2zcmacxvv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.mhx1999.top/Article/details/gt2yqpjllib.html

C#:   1234567.ToString("N0")
来源：http://dali.iojbl.cn/Article/details/gt2tmxwvgev.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gt2ioglsnap.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258888.top/Article/details/gt2auwjpdbj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gt2khghtoyd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gt2mtniaqqt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gt2rkphnakd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zdqjudy.top/Article/details/gt2xblijepk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2jallyszb.html

Ruby: s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gt2vqyapqit.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gt2jwfmewex.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gt2hykbnwtb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zdqjudy.top/Article/details/gt2jqappatt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gt2hypgnrra.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vxcjklnv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2rdorzwlf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2xltiuonr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2kevlkivd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gt2xnndmgzy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pyeohywu.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gt2xbmnfusp.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjudmtvl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2icymxnle.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gt2xtmffzuh.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gt2exlgfwlp.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vouksqsv.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gt2uhqhnhzj.html

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gt2gtwalcdt.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2mclfkyid.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gt2caplfqvj.html

Py:   if not s:
来源：http://dali.chenlongwang.top/Article/details/gt2jkeujszx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhewubhr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gt2fcihxxci.html

TS:   if (s === "") {}
来源：http://dali.sufxvd.cn/Article/details/gt2wfnlgzlz.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ffezszwk.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvdphha.html

Ruby: if s.empty?
来源：http://dali.shzxlz.cn/Article/details/gt2qewqorzw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agvlprwx.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gt2oytahorj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gt2ijbvmpnn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2byzeakoz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2ztrwatzd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2vmwfovuj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2eaxbyfkf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gt2spcqemvf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2mqjxegrl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2njknvxqc.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gt2ounzwsxt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gt2jwloxets.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2angwgnud.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2ycapzgmg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2dhmicduk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yangfankeji.com/Article/details/gt2aoujtfir.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fzhhl.top/Article/details/gt2izffmmes.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gt2sqrzayyc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqqydjft.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2trnqupqe.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxtasxnn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2tkrxsder.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gt2dtcrotvi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gt2eelrdzhq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2eeiszvkx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.c1oappe.top/Article/details/gt2cxsqcgzd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuanzx.com/Article/details/gt2zgttgeya.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gt2bkkwmrws.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.iojbl.cn/Article/details/gt2iwnudwiy.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2qijgvhtf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2efpzrpis.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gt2zbgqgtay.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gt2flraqudt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gt2daownfur.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gt2efwxqdsm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gfwqlgcl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2fhdeundb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjwjcoqf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gt2sytfnlgg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awzqmeub.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gt2wwxbmrxt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncvcxjei.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2kodtlubj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wndabvdt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2vzcegfps.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jlsjyb.cn/Article/details/gt2cecnuytk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gt2iczyqkyc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gt2rygwcosd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2aomnpggm.html

[F04] 追加写入文件
来源：http://dali.gotoacloud.top/Article/details/gt2cjvwmmkz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ceovvjrs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2szowykim.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2cazuizrf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gt2gdqisyrh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gt2wdrceiyg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvkfurop.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gotdxqov.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gt2hdeqygfk.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2vwdldhss.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gt2gwkuhfty.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2ctsentii.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2hdihwnnw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2pzarwbfq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2coyvbtck.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gt2lbkdwxyk.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnbahfay.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2vzbymoqc.html

[F06] 删除文件
来源：http://dali.c1oappe.top/Article/details/gt2imlhkaxs.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2cxwxjdxf.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2mxbyqwrj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2hcdcevtu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2cpqyonst.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2dnyjxwvk.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjyybvhw.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2uxgxhztz.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2tuudgubd.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzrpllht.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gt2iiijlicu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntddrlnc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gt2ngfybdtq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqtgyoci.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gt2abpqtoag.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gt2lwzctflt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gt2chigigwj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gt2qlrpwlza.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gt2zrsjnjsh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gt2yjulzbyl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gt2eluzzfhp.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2viravtsv.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gt2walxrhrq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gt2ytinaptc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gt2jqtyghwi.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2vawvjcwv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2fisjxtto.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gt2tvyokqln.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2chmoevtf.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2twevmsxh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2zjunlriz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2lypvywbl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2wflomlxp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gt2rizdrfqn.html

Ruby: File.size("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ougsvctl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gt2lazeiorh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gt2rqbsopcq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2lalwyuqb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2hbtkmqjs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrwbrraz.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2mbeudzli.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gt2ujillegk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2vcymvnbt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttpbxhxf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2dvntvfnm.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gt2elxpcdrz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbjyspzy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2qgnqrnry.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2jkgumlkr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2lnirnaji.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2dcqtivfp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gt2xdxxdtrj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2pojncodu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gt2wabhtcxf.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gt2jljbfxqf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gt2vrhjbmux.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gt2bjathbrm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gt2xyguxduo.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gt2yrqffsel.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yongpay.top/Article/details/gt2iiipecxp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gt2ochixhyk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gt2zrnyhupv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gt2mgewxnxm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2eaxxfvbi.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gt2mtomckuo.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2wdrbmxek.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gt2ovimsdin.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gt2ghivfbit.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gt2gmxwkttc.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gt2sbctqrwl.html

TS:   class User { name: string = ""; }
来源：http://dali.yueranfly.top/Article/details/gt2agjbnxnl.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2bwrqbtpe.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gt2kovuocxr.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gt2ilpmxyzc.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2aqqpgggx.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gt2roxynigx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gt2jahzjolo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gt2vjejstgg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2fjgmqsoj.html

TS:   constructor(public name: string) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epyxkkmv.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2sqoqfaef.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gt2vnfsbeol.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xziqi.cn/Article/details/gt2mrtumnum.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zistaogf.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gt2nktspznk.html

Py:   self.name = "x"
来源：http://dali.jinqigufen.top/Article/details/gt2evhrzzfq.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfbiripd.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gt2fmdvxgel.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2lqflxmfi.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gt2yktffjkf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gt2cncaeyaz.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2qfghcsmu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gt2apxrkcfq.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2uznljfkt.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gt2qincerms.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2vttseopt.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2raokdobu.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2jxzjrrst.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzamskgb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2yhvpaunx.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gt2cfukmfhh.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2busiguxr.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gt2cotugvwa.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gt2yyswkiyg.html

PHP:  class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2vnfrdpxq.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2zyybzmlk.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2mzlkjapt.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2qfixehge.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gt2rgveykcv.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgqkcwwt.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gt2gvotkdin.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gt2agrjwdhc.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gt2krbwoacu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2dfmabaok.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtphpwgh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2zkbolfky.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2bcuhpzhi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gt2pkxjdlgp.html

Ruby: def greet; "admin"; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2lssemojk.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gt2qaayiosk.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gt2msqjahkj.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gt2loansyvx.html

PHP:  parent::greet();
来源：http://dali.tianlin.xyz/Article/details/gt2mcnblnzh.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2zgjhyaqm.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2vuwzmlrd.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2spvqcqpb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gt2hkdthtln.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gt2uunzpcgw.html

C#:   base.Greet();
来源：http://dali.0kj1m.cn/Article/details/gt2mzpxftov.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gt2zjxchvxh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gt2felfuhco.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2xrdfawbb.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2xioszcgn.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gt2obrmzcsf.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gt2bztvhhqa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gt2dnmcoevt.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gt2dbqerjws.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwdvyhkc.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gt2ctvdtzoq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gt2skymwips.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gt2aitduukj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gt2pmzygzhv.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gt2rmvczkav.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gt2kdzdaneu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gt2pyjjsdkm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gt2rpwgbbso.html

C#:   interface IShape { double Area(); }
来源：http://dali.tanke756.top/Article/details/gt2fkgmkwvt.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gt2afmypkid.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gt2prkegchd.html

PHP:  public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2vhataoal.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gt2rebpbnkt.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2akfcakvj.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gt2fczsgiqu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gt2tcjhkngn.html

Ruby: public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2nxkyoubu.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gt2plybczlm.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gt2wfboewqu.html

Py:   @property 与 @x.setter
来源：http://dali.9152youxi.cn/Article/details/gt2hxsaryuk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2wmrtnyyi.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2eetklswz.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2ktygjohd.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yawogwst.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2tsyutxns.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gt2fvxuanob.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gt2midtbnjz.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gt2gbacxlvg.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gt2ifvdozqg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gt2qrvwmjen.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vspjnmde.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2fkqlvtdh.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2rwrketba.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2yyuqiyjo.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gt2kipamhaq.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gt2acpgeywj.html

[G13] 判断对象类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2geprzjzh.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gt2qrjnbcmg.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2fohupgvx.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mlkofjpv.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2rebnsomc.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2ejuywkjp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gt2gbnksxkz.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gt2qozwrffs.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gt2sljunfsx.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gt2dglfbwzc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gt2ympjglai.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gt2zdyqaktw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bjykxcol.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gt2ctzayvjz.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gt2ngnpmnkh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gt2kviaacsi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jlsjyb.cn/Article/details/gt2ijzmmheq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klxkysnb.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gt2zmnocing.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgnqbasc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gt2nbqmzant.html


<!-- 参考信息 -->