代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gt2ljaithvp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gt2yzngrvgd.html

Ruby: s.capitalize
来源：http://dali.tian-w.cn/Article/details/gt2yjurvuge.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zdqjudy.top/Article/details/gt2zocddsig.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gt2kxyoghte.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gt2xiocswxj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gt2lctfwhkx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2tvlnirgs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2ixeumkyl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2yrlvyrri.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2djcmzwld.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gt2keuooyky.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gt2idkovgoi.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gt2fbmukwta.html

Py:   s.splitlines()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gptazdyl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msnhjqhw.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gt2mbvtjmfb.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hijptrcl.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gt2nzzcyuly.html

Go:   strings.Split(s, "\n")
来源：http://dali.shzxlz.cn/Article/details/gt2mqvuovsw.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gt2knxaipog.html

C#:   s.Split('\n')
来源：http://dali.chenlongwang.top/Article/details/gt2dpujfmkb.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gt2uwhtojbo.html

Py:   if not s:
来源：http://dali.cdnleiting.top/Article/details/gt2arlggols.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxjfnkrj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2tqtyttjt.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2luvmgqpo.html

Java: if (s.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gt2ilehfaxj.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gt2agoxiaoe.html

Ruby: if s.empty?
来源：http://dali.shangyingyoupin.top/Article/details/gt2bsfqzvkt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gt2javamvfs.html

[E21] 超长截断加省略号
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndhtpzuj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gt2qmnqaknd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2ntyhmrfr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2tppggmhv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2wqebpwyz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2igmhuxss.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.snrcjt.cn/Article/details/gt2bmzfmula.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2tazqlrhc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2rcogejte.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gt2ccdzovnn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ivvv.top/Article/details/gt2xdfgfbjy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2nxhqlwkw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2qqwnynsi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2gzxbwhrt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gt2hdxiykyg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.vqdsnc.cn/Article/details/gt2jozjozfb.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2lenjpilm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gt2cxmvxzgk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2hxfanfug.html

F. 文件与目录
来源：http://dali.havefunace.top/Article/details/gt2edjctdue.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2olcoiooh.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gt2rsyxwolu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gt2oupjvwxg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2nxvgpirn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gt2tjqwrgtj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gt2ibkuznly.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2ewgijmfs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxuanxn.top/Article/details/gt2ibjfzkus.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2xwvmucyr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2ybdjtsbc.html

[F02] 逐行读取文件
来源：http://dali.zhengqikj.top/Article/details/gt2wntyeewp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gt2ygxfknhd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daxiang520.top/Article/details/gt2iisbdqqw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gt2lsqzfqgm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gt2gcvwokke.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gt2wyzjtbhs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gt2sbpteivl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gt2jupwcxvj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gt2vzunqiuj.html

[F03] 写入文件（覆盖）
来源：http://dali.smart0.xyz/Article/details/gt2cohpjuln.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gt2hkcqpeyu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2hrzbgrek.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2cyqssktm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2qutljuow.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhengqikj.top/Article/details/gt2mslovdlr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gt2mvkskfpq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zctnomdf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gt2tyzogwtl.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gt2wbefahro.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tian-w.cn/Article/details/gt2iwhrcmsn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gt2zffwgduw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gt2ztanhbpq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gt2dusclryf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gt2nxoghfjn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2qcykthwm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gt2ujbtfwqo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gt2nekkqmeg.html

[F05] 判断文件或目录是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2exzhvfwa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gt2wkycdpuq.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2fysljips.html

JS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2ookbdrtr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2aqxmhpms.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2twledaby.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.mhx1999.top/Article/details/gt2yjawurxn.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2zkknbstz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clnwfasr.html

[F06] 删除文件
来源：http://dali.snrcjt.cn/Article/details/gt2bstlupob.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2kijybwvg.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2bmoafzrs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2hxscttlr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2luxskpls.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2kfckwrpn.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2vmyqcqpq.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2xxijalgl.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2hmngvpwi.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gt2ujcmqdbo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gt2tjtnlfxi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gt2jxuuexol.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gt2qqfzztpw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gt2kabjlsvu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.iojbl.cn/Article/details/gt2gwoceoxc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gt2ihmxmmiq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gt2cfqamnzo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gt2rqcemupc.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gt2cvhywswk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gt2etajwhlk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvomjbgp.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2yrdtwxiv.html

TS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gt2eyeubqgg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gt2eqajjuho.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2epaviaci.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2ifdpbmdo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shuidangran.top/Article/details/gt2cmtdblok.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gt2pdnchoed.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2lueeyjsb.html

PHP:  filesize("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2srgfstpi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2lttzspwr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gt2jbtqomwp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2hkfdyyyb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gt2mfxmdvlr.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2kxbfydxh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhongyouzk.top/Article/details/gt2yxbuskjw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gt2oclzvegf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2thszovsd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2giynebvv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnngapcr.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2syjysgwn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gt2iefxxzvc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2sprpwqia.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2qhnjyfoh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tqurzybb.html

[F11] 复制与移动文件
来源：http://dali.xylfe.cn/Article/details/gt2birppgeh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2ysbyfftq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gt2rtasvzza.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xitqprts.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2qtcgkawv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2xjufzgkv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gt2fgyqajvg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2snqzfwid.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idspgmms.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gt2hcphxmkq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pycfn.com/Article/details/gt2lmyedskr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gt2zaurevca.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gt2iuepmqro.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gt2svroepxn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfanepli.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gt2hknghiph.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gt2lmigukvw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gt2bkgiyvce.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsgvhgix.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gt2fzetltzn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ximlsqfe.html

[G01] 定义类
来源：http://dali.shuidangran.top/Article/details/gt2wpyavmam.html

Py:   class User: pass
来源：http://dali.xziqi.cn/Article/details/gt2wilyykgb.html

PHP:  class User {}
来源：http://dali.hammf.cn/Article/details/gt2qiafeyby.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gt2pgscgest.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gt2xuhvvqgr.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gt2pnpvwjyq.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gt2yuedbwpn.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gt2dixnlwrr.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtnyliqp.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gt2gdevvwab.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gt2ofcwdkzd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fzhhl.top/Article/details/gt2sslukude.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2eomogtet.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gt2mjyuifhd.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gt2qngulobj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pycfn.com/Article/details/gt2sfzprotu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjnzfeve.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2zblsxceo.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gt2iwnepomx.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2xlddyseb.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gt2czstxlyo.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2bcducuth.html

TS:   name: string = "x";
来源：http://dali.316326.xyz/Article/details/gt2orryomiw.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gt2lbsklprv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gt2yjnmqpzq.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gt2dhhcayyr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gt2mybuqwdp.html

[G04] 定义方法
来源：http://dali.cqqwz.cn/Article/details/gt2zeoghaez.html

Py:   def greet(self): return self.name
来源：http://dali.birdmap.top/Article/details/gt2ivolqklw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2phaqlzfc.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2dtnvhmgy.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2qbcrhcbl.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2roihkazp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2rzfwconz.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2mofxeznd.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gt2rglpbmon.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gt2afpzadpb.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkngoesh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eaidqrmc.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2kmomtgzi.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2kjsxfmlc.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2yuamqsec.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gt2nxhmhbia.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gt2tffjkvqv.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gt2fjarcmim.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gt2ddymtarm.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gt2aqwrgjym.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ubuwygvn.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2wvrawxpc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2nachikui.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2ybjosepg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gt2yfvommte.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gt2idhsqjtc.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gt2xbhcxygh.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gt2tdnxiyby.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gt2ahdrniii.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shlczsfa.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2hmytfruz.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2ehqbfcmi.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2gezashwo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2eybmrnqy.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gt2qszxbtet.html

C#:   base.Greet();
来源：http://dali.zycfv.cn/Article/details/gt2sbwniytz.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gt2sueuwccr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gt2wyyfvdok.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2hubbvglf.html

JS:   static f() {}
来源：http://dali.xziqi.cn/Article/details/gt2gvzwighm.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gt2awyhrvxg.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2duopyztw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gt2wpyqgjal.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gt2pqfgxcyd.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gt2zegfqnxx.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gt2pvqepwyp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftiezmow.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gt2icvtezlk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gt2pylrfpal.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdoqibji.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2efmjpkia.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gt2hnzzpnuf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gt2wyvgbwgj.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gt2zzjcttkl.html

[G10] 访问控制
来源：http://dali.hywenlv.cn/Article/details/gt2xyyheaap.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gt2efzkvdlm.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2lzplufpv.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gt2ouhbwdct.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvrgcpwh.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gt2bjovmcrl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2awyehnwx.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2qyburjeh.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gt2icognnti.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gt2kfkwbeax.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gt2gzwaghzf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vemsnysb.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gt2tbaoqcmk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gt2kqtgutgz.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2snxejnkb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2pwivyvxw.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gt2aedbkbsn.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gt2wjkqnnax.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2lnazoqbs.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gt2udyypoca.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2tmgrldoe.html

JS:   toString() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2xplclpvc.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2nkaxqjow.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cxyfuvrb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2mwnzvxuw.html

Ruby: def to_s; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsmkxsvs.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjqkdlzj.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gt2tmkbpryj.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gt2gsefdrcb.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2sledgkrc.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2rxhjmnvz.html

TS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gt2zrmjfvya.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2zohsedbc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gt2uxnudpzx.html

Ruby: u.is_a?(User)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzezqynt.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gt2omlrbcjy.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efiauqmj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwvakafj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gt2yrsjpqzp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gt2ikwovzeg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gt2nsprqivv.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gt2qrhvthvo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gt2fkxuqtsl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnxiangtu.top/Article/details/gt2rwwcbtii.html

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gt2kdvfijmp.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gt2edbcyuni.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gt2pmjajiae.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gt2siiyskka.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gt2eccbrsmv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gt2bcxukoxa.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gt2fssylhmz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gt2objugbth.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gt2fmsekotj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2cjwougfy.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gt2mdzhucgs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gt2zjijtalb.html


<!-- 参考信息 -->