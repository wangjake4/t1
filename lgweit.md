代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gt2aidrwvvn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2ticumvss.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gt2umfrywnh.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gt2wyyqwxui.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gt2mfgrexna.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gzhubu.top/Article/details/gt2efrrzlwn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2rvlaqweh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gt2pezysgvx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nwbrower.top/Article/details/gt2zvymqllc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2lvindskb.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gt2szjiawfi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gt2beeuekhx.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gt2nknhcbnx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcbnfwpj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dianchejie.cn/Article/details/gt2eevrjgmo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2jniljuyo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2eayylzil.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2elsqyugd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2pranhkuc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvuiuzez.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuanzhike.top/Article/details/gt2fixtzcwq.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gt2bsbmegvp.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gt2yycfkrqx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2xigmogve.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gt2fxpnsoxm.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2vkzdhjai.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2szzlozdv.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2rxevvacg.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkurcevw.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gt2zfnudbgd.html

[E20] 判断字符串是否为空
来源：http://dali.iojbl.cn/Article/details/gt2psbhhngn.html

Py:   if not s:
来源：http://dali.shzxlz.cn/Article/details/gt2uszjadxr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2laiksqgp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gt2vfxshmet.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gt2kvbpmvin.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gt2zuwmqclv.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gt2xjawznmk.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gt2ytlmrlua.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qibuajhr.html

[E21] 超长截断加省略号
来源：http://dali.jianghu66.top/Article/details/gt2gloszboq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gt2rokjtzew.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gt2pjmqtntp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2aprkoclt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2mgccjdev.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gt2uhlvxhax.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yueranfly.top/Article/details/gt2qipdgaan.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2mtwlgijk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2xegaxylc.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gt2yzgtjysx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hysaishi.cn/Article/details/gt2erlpgvvg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2qmagyxzf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2kbmoplao.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2bimhnicf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gt2gibtroty.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gt2hgbjcwhi.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbhxzuyo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daria6918.cn/Article/details/gt2yspzfmrl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2pezofbnh.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gt2nuwoqoxw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2amwrrjky.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdfmbiq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gt2uhsxdvou.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2nuslztpf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gt2bwkllfsv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2nkiybgan.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gt2zkffricx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gt2nmzhtdug.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2jxsyaqhj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2wkdfadlg.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gt2xowmghcv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gt2oghakzaf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gt2swotwkvn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2itojcscm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgisyhke.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gt2jtdjznim.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gt2qxouhnxk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gt2vyreztyy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gt2pzeagiqv.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gt2ndmlohec.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jlsjyb.cn/Article/details/gt2sspgpteh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gt2mpbwsapu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2awiymvnu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2yoazzjyj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gt2xpvusdpi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gt2vdmtjadh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gt2ghdrujbd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ootzseva.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gt2oyqhppjw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaeencnf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvzncxoz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2embmrtef.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ssmflgpx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gt2ykwfxyht.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2pfjiqmxi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gt2glzojtvk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gt2neogzseo.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gt2yhsjjzeb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gt2rnpiwwjv.html

PHP:  file_exists("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zofbxdlz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2hxxyitje.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2uqwmbldd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2vszqwtwv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gt2uppiyaak.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2joixrbym.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lfojvnbn.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gt2azwqjlko.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2enzgrgub.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2amvviozq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jrdldjlw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2xemhtune.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2dsbyhbgy.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2kpytrlzb.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2egteevjy.html

C#:   File.Delete("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2uedkeubo.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gt2yanhwsqx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ibyswttx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gt2dawmddbt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2fnshldmk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gt2hrhifawy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gt2wqbiwyce.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gt2yecumeuf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhbctlro.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gt2powmchwf.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gt2rmolehdq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gt2wkkedity.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gt2nhjfzprd.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbwyippn.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gt2hdmsrpgu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgkbohyi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2yhmcxzre.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2vyhhurxn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwdkohrs.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gt2zavkanup.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ptsznvil.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2tatwyrij.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gt2vizsxzzb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gt2bneyevct.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2bulturqy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gt2roumzule.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckynbdmn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gt2sopgywxp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gt2nsinfssx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlulqtjj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2nzxrqksv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2jvevhojv.html

TS:   path.extname("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2jhzywfzx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwebsboh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2srfibxnb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2bpcmwlsd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2qjyfqveq.html

[F11] 复制与移动文件
来源：http://dali.mhx1999.top/Article/details/gt2rfdgulid.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2gdgktdpp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gt2eytqfsje.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2cpokzamh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2pfgxogmg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gt2euqspunn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gt2hplfgklp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2wkwnlodr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gt2dcazxegv.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gt2stutfdgi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gt2yjmgvnvu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gt2aosixvpg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gt2bvreiiai.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gt2nlsnuwzv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gt2umetbrnp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gt2zgnoixvf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cashguo.top/Article/details/gt2ttaqmdsn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdyexjuv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2mbxkghdc.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gt2ezzjsrak.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2shhtrzat.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gt2flgmctdx.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gt2ygvzzxlx.html

PHP:  class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrxvytlw.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2xdkyaudy.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gt2bmryeypq.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gt2bxswqgpi.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gt2qzcmtvtt.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gt2ihnmyjjg.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2zogghqgq.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2wtmqlewj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gt2osqkhmdi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gt2ziwamdix.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhctvukv.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gt2jiuyrceu.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2dciytdbs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gt2vmngszeq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gt2pyxugaza.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2teijbizd.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gt2cycigxmj.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gt2rttdxeqb.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2alluqpnx.html

JS:   this.name = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2fnzxmfmh.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2enaycrfz.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gt2ialagimu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gt2zmmjtzvj.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gt2ruzfzqwk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gt2diantiri.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gt2zcwlkpwi.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gt2xvghskgi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bxywajaz.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2iiffythw.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2medbpomg.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2ptnxsipa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2pwugmvmq.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gt2vkefkcyc.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gt2watdetdv.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gt2aevahlaf.html

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gt2vefcwxom.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wudarqeh.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2tsqwmueo.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2vqghcjsn.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2llkdshej.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daxiang520.top/Article/details/gt2ivmpoari.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gt2jxpruasa.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpowedop.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gt2yececczz.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gt2lpaimbzw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2jygyyywf.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2ipxdxgnz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2rwjjtphw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2meecscox.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vylqayle.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gt2smlwqalp.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gt2xnzmiuzc.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gt2awisflqo.html

Py:   super().greet()
来源：http://dali.havefunace.top/Article/details/gt2kmqrqstg.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2amlwmjaz.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2ceedntlu.html

TS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gt2jqkshwkm.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gt2gvvsiemm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gt2vukosdtq.html

Ruby: super
来源：http://dali.shuidangran.top/Article/details/gt2mzopdcif.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gt2bpflxxtc.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gt2laxpmrmb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gt2fqgzmvpd.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gt2fecfvrfu.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2qsjjfjnm.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gt2bjdahtrr.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2zymbzjsq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkvlmxdy.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gt2oqqcbxya.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gt2evexgwoi.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gt2kynlslvp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gt2jxxvjarz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eychjlfx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gt2kjvrxsdb.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gt2amggzper.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhvlooxm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gt2rqisieaf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gt2vngdqocb.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gt2ldhqhniu.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gt2ujqkooyp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gt2cppatxve.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2xwephrsw.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gt2rgjuisld.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2gefgbucb.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gt2zlxuprqw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gt2iasvmyyj.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2qbunkcfc.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gt2abfxcxvd.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gt2ajgwejep.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gt2vegnourl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2nmwqmrid.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jlbkrllo.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gt2epkkzeuz.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2owijtstn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2cdipwdyb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxlxbxi.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gt2gkhxqsam.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2lahxhcve.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gt2cdmwfceq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gt2yppjytpr.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2qtutrauw.html

TS:   toString(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2ansaldhi.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2xyleyxen.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2sxzvoavi.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2xusfjjtd.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fuhujgiu.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gt2zzodcuhz.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gt2kujdekqe.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2slnlasyo.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2ayjklxpd.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2wkchjujl.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2pbngslpm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gt2rgfwwtxw.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gt2uynmqmar.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gt2lgkmcape.html

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gt2owmyjwqb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gt2jcecifoy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gt2dflqvumy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cqqwz.cn/Article/details/gt2wjitkozq.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gt2ptyebdhz.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ermowbes.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gt2afieojif.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhdrbyyq.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwmefmvt.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2tmqzxsgc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gt2wsbtimsc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gt2uanyztwe.html


<!-- 参考信息 -->