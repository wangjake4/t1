代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gt2upekjkkw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gt2dvdxmayy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmbmdhob.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2cqsdyamr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ivvv.top/Article/details/gt2urdpgrjf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2lwkwkoxg.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gt2vencpomf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gogol.net.cn/Article/details/gt2xweuvtls.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gt2tczorvdr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gt2srvbaziv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gt2ehimpgmt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2yfuikstp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2vvdjzugi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwxfkmwp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2ebjjmqyt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2cvximlvy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gt2ridxaofg.html

[E19] 多行文本按行拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqnbxobs.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gt2oddxdwxb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2eiurjchd.html

JS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gt2jphnidve.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2bzfqyydz.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gt2vczjfrwp.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqbklwwt.html

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gt2elolehcx.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gt2lpkfsjbw.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gt2vvuagwav.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gt2tjrznfyu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258.top/Article/details/gt2atwxbweb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hfpthk.cn/Article/details/gt2trykambi.html

TS:   if (s === "") {}
来源：http://dali.wangdashe.top/Article/details/gt2tuogrmww.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2excxqbov.html

Go:   if s == "" {}
来源：http://dali.dashuyun.cn/Article/details/gt2rrnjmhoi.html

Ruby: if s.empty?
来源：http://dali.fzhhl.top/Article/details/gt2wjhenqdy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gt2pvsbjijs.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2amiqycae.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gt2igtrddii.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2msfevtku.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2yguaxhdu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2ewibbple.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2xmozausc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gt2wloyfpgx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2ziamiwvd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2xdpcfpwu.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gt2iujgvaxi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gt2swntxryi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eovramdk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2mlqjdoma.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2cyvyvgio.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gt2azejtqsp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gt2bhyippye.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2yezrqnys.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gt2dpiruwpm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2tgdtachy.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klfxqjtd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2oyvepnhe.html

[F01] 读取整个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbokacpk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.havefunace.top/Article/details/gt2jmcgkgvj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2miukyhcl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gt2lglfvnqf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktfpmmwg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2ovaxckcn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangdashe.top/Article/details/gt2mswxeobi.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2lhzylsyb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2aijfzpax.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2evcawxze.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gt2hxujudkq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cqqwz.cn/Article/details/gt2haxysljc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2soerczmu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrctbsfg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gt2kjjdbxve.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gt2bmdsekpp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbzupxt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gt2azmkxpby.html

[F03] 写入文件（覆盖）
来源：http://dali.birdmap.top/Article/details/gt2jcpogqqi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gt2xzpuqlwu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2zhpaicjc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2onbrtrmj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2hnjdbxlr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gt2kroukzrl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ziphvlwy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gt2fyeagdxd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gt2geioqfma.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gt2fykyedtt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2eqaeofaa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gt2pwguxtvb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2ublmqnrr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2mkhrkjyo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gt2bpjpiqyt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gt2ktyatgkh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gt2gwmdyvrj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qttpysai.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gt2jpxnpuma.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gt2cyuqosxz.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2cqckhujr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2lemmlzcb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2penxlmbs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2ftvkrdkp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gt2xjjtmzyv.html

Ruby: File.exist?("a.txt")
来源：http://dali.sweek.top/Article/details/gt2ndmpeeih.html

C#:   File.Exists("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2gmcmnlas.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gt2vexqrplm.html

Py:   os.remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2zedtkdpl.html

PHP:  unlink("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2fthgorkp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2iquecuti.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2bihwvoft.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2cmbznhlp.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2iaumzmxe.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2tcbesrum.html

C#:   File.Delete("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2ghsjutlh.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gt2foqzipcr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gt2ciikormc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gt2khhzwysn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gt2mdxnphpq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gt2yscnrhjv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gt2axqfirns.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gt2ylrsohci.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gt2htrzaljl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gt2dbwkpkkj.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gt2bfumxaku.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gt2ifqffpoz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gt2ldceuccx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2nowimgsj.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2ouyvncnq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gt2daedjhyz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elhldydj.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2owjnkswu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gt2pjwihmbi.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gt2zkkqfbrs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2xbchwqmc.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2pilpwdye.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2kksexjen.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qscalxdy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ddonikop.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gt2dncgfmxk.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2fhapbppd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gt2riuztthi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gt2ckrslqcw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2pjecgmwy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnvhofzp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uludlvew.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2ecyfwqgr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gt2gteczcsm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2bzvudwim.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2uzkufvlg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2kpjiwfga.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gt2uacfrodg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2wweoqily.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gt2gewqwuhe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2nekbzjde.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2bdrnolov.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zaczxdqk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gt2xsnjkpdb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2fjsoxafs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gt2wpdzdeub.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gt2yrdehnxl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gt2bbnvwngy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gaohongyu789.top/Article/details/gt2mnnunizn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigfzy.top/Article/details/gt2yygyotlt.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2jvjsrayg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gt2qyasdzod.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gt2kwihqkxi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gt2xlbrgnmi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gt2sfzxjzsf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2kpysikcc.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gt2rdrudgle.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2dppconid.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhbuezgy.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gt2aokikhox.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gt2ketppeia.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2vaujhfvs.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gt2vyhcpnbg.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gt2hmjwotld.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blukelht.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gt2shxzatzk.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gt2vqzcspuw.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2seggebdj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gt2wktmfhkw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2murcpspl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2fdvqeqnx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqrybgl.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yrmajwvw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cpvehnol.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gt2bqzqxjlg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ilwtkehz.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gt2tqdlkuxo.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gt2dbplwyah.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2aswhqxmk.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2cagpqwba.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2wdpcxxnm.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gt2gfdmwqoc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gt2lkqpcpgn.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2ezquprul.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2nkdirqsk.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gt2zrbstzie.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxfjntbx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2hxvzbhfo.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2jxdctqzg.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2mhhisydi.html

Java: String greet() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2gwebtmrr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2wqcckodg.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2fuqatalk.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2dvvrmhcb.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gt2dokljuwv.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gt2mjpmourl.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2oozodhkr.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogqkgonh.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2lqrahbge.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2yhpmlana.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gt2fdgizlzt.html

Ruby: class Admin < User; end
来源：http://dali.hnxiangtu.top/Article/details/gt2vdixvykr.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gt2cijaudku.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gwyxcoud.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gt2gvhuuozc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2khyuynaf.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2plnycfkg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2przaibkl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2zofeoptx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gt2bdtxjldm.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gt2ibbeopmo.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gt2zsndcjpn.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gt2sbijkzua.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evclvqgo.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulqphapa.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2azpkplbu.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2yruefuvq.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehwefsdv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gt2fuauoykq.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebrnraby.html

C#:   base.Greet();
来源：http://dali.tanke756.top/Article/details/gt2zfszzffp.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksofdcow.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zycfv.cn/Article/details/gt2mzlamrsv.html

PHP:  public static function f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2bhkzudty.html

JS:   static f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2azccnjuo.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxzptiwb.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gt2xfxfmyee.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gt2mjxgqaxa.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gt2gumrliqz.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gt2hgpjqviu.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gt2fvleqpns.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gt2cnsmtzgj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gt2gogvigmw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gt2zgbvqntx.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gt2cbjprjtn.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gt2wjeqyodl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gt2opkjfjoq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gt2vqabnqea.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gt2rbgixpyg.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gt2qnstntor.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gt2aioccadh.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2jqtwrkzz.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gt2iqbthfoh.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2iuebesny.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gt2anljvzpn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gt2rfhebpke.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2vjeljxuf.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gt2qgdjqmsi.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gt2kblbkleb.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gt2crbpdhsz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2bzfmzsax.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhzdcydc.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gt2ubvbdggx.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2xnoezacm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2mlepmkvd.html

Ruby: attr_accessor :name
来源：http://dali.yongpay.top/Article/details/gt2iukvynlu.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gt2ysuvhxrx.html

[G12] 对象转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2rmzdxrpt.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gt2ywapmoid.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2ooojdapa.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clmbmxbh.html

TS:   toString(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2axadvyuf.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2wsuohjna.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2oyejsnne.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2xrlcpewn.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gt2tonpgdcq.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gt2yfdvrlaq.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gt2kiaoywej.html

PHP:  $u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2guzxcrcl.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2hjdqwxnf.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2drzueuui.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2udoahofb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gt2bdfjdecn.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gt2cgkkwqrr.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gt2bkfqrcqd.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yuivlryg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cqqwz.cn/Article/details/gt2pnrhuigw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gt2okpfhqzv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlbqaohq.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuanzx.com/Article/details/gt2titxtnek.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gt2puqhelsb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwyftdmo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gt2fshdqobn.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gt2ujgyagrs.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gt2hlzdbhwd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqffvdnt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2teeyputc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogaxjtiy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gt2cahzutyk.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gt2bvddlvvz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gt2gknfgvyo.html


<!-- 参考信息 -->