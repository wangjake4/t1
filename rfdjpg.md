代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gzhubu.top/Article/details/gt2rnfcbeeq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2cffsuhhy.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gt2rqfnambi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gt2ddlroohz.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gt2umnaqxxw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkgqovn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gt2qihmwirt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2gggzfiqo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2pjpvcpmt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2kjljsixa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hammf.cn/Article/details/gt2boizemne.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gt2opgvnfth.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gt2fcsbjsch.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gt2zrkvddhj.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gt2orsupuqq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2mrmassmj.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gt2ebnpeqna.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gt2kdityrmk.html

Java: s.lines().toList()
来源：http://dali.ybcxt.top/Article/details/gt2ppzbovbt.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2eiadnknr.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gt2zxaouubi.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gt2zsxhuedw.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2duyimyiz.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gt2jbnoonlm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnonzmwz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cheryme.top/Article/details/gt2ofzbrznt.html

TS:   if (s === "") {}
来源：http://dali.fzhhl.top/Article/details/gt2srlwltib.html

Java: if (s.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2dveihmjw.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gt2crykxtfd.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncheemgc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gt2wqhlzmxb.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gt2zeoskifd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ppjwa.cn/Article/details/gt2jyjiulqo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2gybqfasi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2itcircat.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2churbqut.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2rstmsslo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gt2ruehwsiz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2mesdaiof.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2mvtrkhzk.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gt2ujnouowj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.meibo888.top/Article/details/gt2jnpxcjae.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2rpyvcjyb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gt2siyenknu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2symsepga.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gt2gdgzrjnl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gt2nobomzlb.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2qstogpfc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gt2znkoyinw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2opccdmfm.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2curyrtoq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlzuekgi.html

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gt2fqlpxevv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gt2ddqcgswe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2xdlcotde.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aizwys.cn/Article/details/gt2osgvdsbz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2mtgtkxhh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2funfydjv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gt2niclvuut.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2fupfvjgn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2wbnsqmgt.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2mepahqda.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yonumen.top/Article/details/gt2fvwydjdb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gt2slcanozq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gt2ejewlani.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gt2axoptucb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gt2jmocuxsn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gt2cgenjmof.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sweek.top/Article/details/gt2lkukuctg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aibaodan.cn/Article/details/gt2tasaugtt.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigufen.top/Article/details/gt2nhmkqlwm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbeqnjmx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gt2cnykgjbg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqyytehn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkxvqaol.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhongyouzk.top/Article/details/gt2tfmfbtla.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gt2axpilnku.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gt2lvjiyltg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2rjiwqgsg.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2eefhycpw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2qrchdweg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hywenlv.cn/Article/details/gt2wlxdgnsd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gt2zhtyssjn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2imbvrusy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gt2cbqukden.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gt2bnezoxgw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.0kj1m.cn/Article/details/gt2pgglhako.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gt2kbvwxggh.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2yswlcqan.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gt2vkkojosy.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2pjlcghbt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrmbtlyx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2gscguipf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2rerijxnd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gt2pdtvhhmp.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2clszlgnk.html

C#:   File.Exists("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2ghzbbrmj.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gt2fsbuhuce.html

Py:   os.remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2ylrkfbgl.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gt2zxlntfxm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ygtifxtl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2gxzgboiz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2lefdwyyj.html

Go:   os.Remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2rynbmwlw.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2ejeothfw.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2wyhhgase.html

[F07] 创建目录（含多级）
来源：http://dali.ivvv.top/Article/details/gt2bvzqtgen.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gt2qbvqwlkd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gt2bbnkhglr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2cblxgxaf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gt2vqqyeubb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gt2gjejemhj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gt2xtgsftpu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gt2klflfeqy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gt2jkguoofs.html

[F08] 遍历目录
来源：http://dali.daria6918.cn/Article/details/gt2slpdntdc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnqzz.top/Article/details/gt2voxaurlm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gt2itmnrloz.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2vthjfjny.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gt2wudurewd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gt2gdygxuwe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gt2hyhuamom.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtcjcfjf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2tcovvsme.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gt2ppqbfxeu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2otssfqph.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2ngibgpjq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gt2qmfdejhj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2rdftaprc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2ykxombfq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqjxxeze.html

Ruby: File.size("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2giifaytn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gt2npcddlkt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ivvv.top/Article/details/gt2vagcqgru.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2awyutdcj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2nxpllxxi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2antvjiqd.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2chzakyoe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.redwolf501.top/Article/details/gt2mmvgxyhx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2foxrratd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2skilwptg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2wtxdvvln.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhfokblb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2tdtqekim.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gt2cjkjjuvh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzimacmt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2mwupslac.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fengsongda.top/Article/details/gt2fqffwpce.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gt2exttwvey.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2ddxmufvi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenzaomai.com/Article/details/gt2xlphyfaz.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gt2phigrzfe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wpedshyh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigfzy.top/Article/details/gt2jutdlyxq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gt2rigreumr.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gt2jvzzoohm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gt2ukufzcdx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gt2ulalmoay.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgufenzy.top/Article/details/gt2rfjmpdve.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gt2pyhkfqjl.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ijxdceyi.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gt2emeoqfbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owuahdyt.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wffaqwyo.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gt2lkatopug.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gt2lrsptonn.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2oqwcvxsh.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gt2lphpwavt.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2asxfgjag.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gt2wpayzopg.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2flqvqsfz.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2giajosjw.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gt2xbefdnth.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gt2niezznkt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndohyhbh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gt2qngadffz.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gt2lmfqzbqn.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gt2pvvbyxss.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gt2errgthbn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gt2cqjwrpmw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhaccqdr.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esribwoi.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gt2rltrubaz.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2kbjgeoxc.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2gwxyqhmo.html

TS:   name: string = "x";
来源：http://dali.ivvv.top/Article/details/gt2zuwtehac.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gt2fidayrws.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gt2lbptbmkf.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gt2zocxqnnm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrfrxjt.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gt2vchioplc.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2yxeyzxus.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2gpvcthiy.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybiblixw.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2edmbxvwe.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2bqymzimf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2qsosbzdy.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gt2nuoredsl.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gt2hdqwlyke.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gt2rycbyvui.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gt2eudxvxup.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2cpdhywbk.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2zypljbqo.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2zmrkearh.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2vmglwool.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gt2sdgsuhdn.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gt2vlapcacg.html

C#:   class Admin : User {}
来源：http://dali.jyoumei.cn/Article/details/gt2nvqyrzwn.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gt2oekqqfen.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gt2pewnsjnh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2yuzjjnbr.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ukxcrlat.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nylhvqdc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2dvnetwwy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhengqikj.top/Article/details/gt2elwesfzl.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gt2nendnoci.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gt2zlaicbxp.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gt2hlgpwmqb.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gt2pjyiqhlw.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gt2bfmeddky.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yeducgjl.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2zkoczzxl.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2mqzsmpsq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gt2hmynnzfj.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gt2cvhqnpfc.html

C#:   base.Greet();
来源：http://dali.xylfe.cn/Article/details/gt2gjgvoaca.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gt2tclvnsqv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gt2ulqpokge.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gt2gbkwiyef.html

JS:   static f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2hbgpvijx.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gt2yhpovhxy.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ipvdnbkc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gt2qedlpybx.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gt2xexjyrxr.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gt2egqtuidc.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gt2vtxxlohg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gt2wsfhdsqa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igakdnlt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gt2hskkstye.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gt2cksusycg.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2llxfzfyx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbaxtqhb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yongpay.top/Article/details/gt2cnhgjrix.html

C#:   interface IShape { double Area(); }
来源：http://dali.hammf.cn/Article/details/gt2keewwfkw.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gt2lxtmqwrc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgsyrsby.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjvurwgs.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gt2tvtdtspn.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gt2wclaqooi.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gt2louyuhtc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iadaxtwz.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2uignfvqi.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hojubhia.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gt2abiusazh.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2kgbxvofn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pognahdy.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gt2zmowvzlz.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gt2yygeimyn.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2yrrecpex.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2uffrfuid.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gt2hqvnmycx.html

C#:   public string Name { get; set; }
来源：http://dali.gotoacloud.top/Article/details/gt2nzbhtegp.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2reykshel.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2esjgcnwt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zzsuwewu.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2kiwpiube.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2orglxtee.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2vcriheds.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2cjqcssrw.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gt2cyjgkgdn.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gt2hozkyoly.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gt2rgyyznoj.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gt2qhklqwya.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2golyvhpy.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2ntbfqayz.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2mmnozwyu.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2lljxrkvk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gt2oascqfqf.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gt2pmafvyif.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gt2hxpgppjv.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gt2wxmylylw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhongyouzk.top/Article/details/gt2abkratib.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gt2zmmglxep.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yanxiufei.cn/Article/details/gt2pxbqnavn.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gt2tpzwclpv.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gt2txyvmizc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gt2kmeglkck.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aizwys.cn/Article/details/gt2jcowridh.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jgcsmgal.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oyunjnej.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gt2xxihzqfg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gt2rczigbie.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gt2rihlypqv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2qlbkbcox.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gt2rsbmsanj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gt2tfdxjmep.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gt2meenfadb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2nxazgptx.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gt2akdyfyii.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gt2tbidqehs.html


<!-- 参考信息 -->