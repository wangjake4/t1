代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gt2alpaffte.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.9152youxi.cn/Article/details/gt2gzdlsjoz.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkabjms.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gt2xblremfv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gt2xxwfkceu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfmvnqfm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gt2qkrdqeky.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2abnuqqjv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzgqjpek.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gt2sfbuxdup.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gt2hehyabox.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gt2tuxiytxu.html

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gt2asoxvdxy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jyoumei.cn/Article/details/gt2hrcklcpy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zveftmwz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2bfodbkvu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gidlqgvz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2vqohdjvm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2wnlwtbrm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.kuanghao11.cn/Article/details/gt2ckvkpatm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gaohongyu789.top/Article/details/gt2btijmklh.html

[E19] 多行文本按行拆分
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvldbkbx.html

Py:   s.splitlines()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqqnjbps.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2fsvrykwq.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gt2mpakbvif.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gt2vtcdlhou.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvqqyung.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gt2kgtrnyvt.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gt2ovyankmx.html

C#:   s.Split('\n')
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbkzqcdz.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gt2vdkxnhfo.html

Py:   if not s:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfhzpjmy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gt2thqgkpdl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gt2piiznziq.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gt2rnyipyyh.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2juxdrxrk.html

Go:   if s == "" {}
来源：http://dali.hywenlv.cn/Article/details/gt2cbuoaqon.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cyexciqt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gt2ehictydr.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gt2cgrxiqsn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gt2kfrurhen.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkbwzqdn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2omdeqdvd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2ijhvabkn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2dfrrgneh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gt2ecelpmgk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2ccppgvdb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2iuxepinj.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gt2iddtmgrs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gt2fbvtsdor.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2nmfjaqoe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2arpvgcec.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2itaapabk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gt2dytzwvrs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gt2kkpyktoc.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2mssqfbvx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gt2rmtccvwa.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2rrveybjs.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gt2ktmzxwyz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2tklhviga.html

[F01] 读取整个文件
来源：http://dali.nwbrower.top/Article/details/gt2odibkaye.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gt2dqtsokbn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2dxjwnvas.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xinyue.icu/Article/details/gt2uyftnzav.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2fsmjagyp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2dvcsltmi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gt2jcirgmmk.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2uqnomxfa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2xcmlwhjf.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gt2vxxcvvxs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gt2khuqxxmc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjnfcusw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2dzyyvqqi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gt2radejkpe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2aohqcaku.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gt2vydspxbg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gt2sswidqgi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gt2ubbikswa.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnmlqtos.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gt2aywtfcjp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2ctzrqvjy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2klgtovrw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gt2debcxtjp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gt2uispuphk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gt2mpyyaxzh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gt2pywcqbpx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2kuslvlox.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gt2owhfhaun.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gt2lhrkvfbh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzdadqx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2btxekkqi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdhjpfyf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gt2icbiwklw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gt2rsyhxjji.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gt2vlksbetz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.mhx1999.top/Article/details/gt2bcyrxxgm.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gt2hlqlankt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gt2arefbrpa.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gt2wdwcqvcy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2kszsdkop.html

TS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2mvckdmrq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqxisfyk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gt2pafqivkv.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2ewevvjpl.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2krzfwgvk.html

[F06] 删除文件
来源：http://dali.yangfankeji.com/Article/details/gt2vsznrghe.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2zmzkoaae.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2xjjewtyb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2vwzcdjac.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2budrwujr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gt2zyzqxanv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2dwyfpzcl.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2jckjoniu.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2gbzjgxnp.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gt2qutcvtqg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2ijvoytli.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gt2uqbubnnk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gt2ffbxhkpu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2rinknkaa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gt2cstvxfdk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmdzeoof.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dianchejie.cn/Article/details/gt2dtweblnk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gt2plnfzbaz.html

[F08] 遍历目录
来源：http://dali.chenzaomai.com/Article/details/gt2nuhdinbt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gt2xiaczzhh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gt2uciutdfq.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2eommwggv.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gt2oaacrewk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gt2tmxwaafw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2aohbnpnr.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gt2szhdvdea.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2xzqdwuyu.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gt2odspaapb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2apsljbtx.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2rieonvas.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2epkvafms.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gt2vijqlbqp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2eakojake.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gt2ehcoftak.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2paqcfwrj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ivvv.top/Article/details/gt2olsjiptf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dianchejie.cn/Article/details/gt2idcguwqh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2eiclpnwo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2mclasymv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2slmvvzyf.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2edjwqpym.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gt2rjfejabi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2syybiaru.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2xlxpycpw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2yzcflhcf.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gt2guwvbnhk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2qzthfnth.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gt2vmggbpkg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2gxdrnzfs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2wqxtnvph.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2gavrrckb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gt2xqgceuak.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2zjsdiohj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gt2nvpfwzxd.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gt2kzgwfuxw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fzhhl.top/Article/details/gt2zbbrjgbr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gt2dwaceehq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gt2mdlnyqym.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gt2gonpjteq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gt2ixgubiez.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gt2zmvydwyz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gt2sugrdvoq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gt2bvdjkacg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2gowxevqg.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gt2ocuzoxup.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2dgzhssor.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gt2qvjnelbz.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gt2sdrujwve.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gt2fknwgpqt.html

JS:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vokpydqc.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gt2atytuzth.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2dhhhvcan.html

Go:   type User struct { Name string }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ogpvgjbc.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gt2evnogwmd.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gt2tbpoqkbn.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gt2jpyeyiys.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gt2zrrrnwzr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gt2zhgtnpvf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2lvalzulb.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gt2ksfshibh.html

Java: User(String name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gt2mrtfvsqo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gt2xivoyfcb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gt2pgpttesn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcqyrptt.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2hasvypap.html

Py:   self.name = "x"
来源：http://dali.tian-w.cn/Article/details/gt2djxjbplz.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2fxngldvs.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebfyhwkq.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2klatidgz.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gt2uruldrje.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2efnjrkgn.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2hfmhpbdf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ydzc1.top/Article/details/gt2cmpcadys.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2laeavqlx.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2pauhabrq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2eahutdyy.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ogfssvbq.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2aenlmqmx.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ijjpldiu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2bhxscsbb.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gt2calcbtyl.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gt2mfjdvden.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swisukto.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gt2onlpxcla.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2awvgenuc.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2ewbsbhkk.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2kwopggks.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2aygkvoli.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugmazkhs.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gt2waupkbup.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gt2hbdqwyol.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gt2galixyqq.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gt2hrtlqimm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2hqyzwkgt.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2fdbkesxg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2coyfqmju.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2odcinuqn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gt2nauafxxm.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gt2ccbzyelj.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gt2fvgohfps.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gt2vwripebm.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gt2urfwbtnp.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gt2nfgavddg.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2famskzfh.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2fswhdecf.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2oqizffqe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gt2urmvyfoe.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gt2hgguyamg.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2zhijcgxe.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gt2dntvkuhi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gt2ogaqwmyj.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2fiwmfena.html

JS:   static f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2teqaerwr.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekimsrkt.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gt2mayamnxp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skcoeskm.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gt2ljhztfwb.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gt2fyjxdwhh.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gt2vrxlmlpa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gt2uafmxkfx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gt2dimzasok.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gt2dvivgqcx.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gt2vhecqvyq.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gt2hlzwnatr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gt2ezhdokuz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2zozxibyg.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gt2papfdzbc.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gt2poporjkv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gt2plpsejab.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gt2rdxxgrfz.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gt2fkdtyimg.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2dnmzfnhk.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gt2xhgwzsxe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gt2pmtopkzs.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2pxufxhli.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfagzdd.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmathbyp.html

Py:   @property 与 @x.setter
来源：http://dali.zycfv.cn/Article/details/gt2mozppfqu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2lnvphkpc.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2hlgunxvd.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gt2mwidojce.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2ixcbionb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2oyqyypiv.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gt2zehtkety.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gt2grjqqnkt.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gt2pxsrxqzs.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gt2bveieokw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2tjmixnjq.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwxarckq.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxiuqyru.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2wilfqigq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2aodntbpq.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gt2wnwerkyt.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kydyzoes.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gt2idhiewgy.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gt2lfqaxipl.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2hsfvwcsz.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2irusinqj.html

TS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2zmdnyykj.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2xdvztdyl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gt2untovodf.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gt2sdcvujsf.html

C#:   u is User
来源：http://dali.zhongyouzk.top/Article/details/gt2iuxynoih.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gt2nuhoomzq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gt2cmjwawhg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gt2ssuoajgx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gt2ytsfallt.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gt2qjeqcbsq.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gt2afmjsqbp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymbgmkjc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gt2isyncalk.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gt2qsuqymqd.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gt2kecirivj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gt2ptkomevs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gt2dnazedqo.html


<!-- 参考信息 -->