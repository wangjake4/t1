代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gt2utmlmzmc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gt2utelglsh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gt2efyvqhpf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gt2rfxnmofp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxoadsal.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhoulong.xyz/Article/details/gt2jltcpjyo.html

Ruby: s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gt2pjeopcnl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xylfe.cn/Article/details/gt2gnhtcydj.html

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gt2efkvubtf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gt2gzegrgyu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daxiang520.top/Article/details/gt2qmcuuyfx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2pluiiesc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2yxfitqyn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2vummlqbx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2vwtdxlfa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gt2khisrqxg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gt2nkepfige.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gt2gvuiottg.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gt2pdmmezjm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2qaqbxqrr.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gt2qtsbgeuu.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2cmwrivnc.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2wzwqdgoa.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gt2gtklqdfa.html

Ruby: s.lines
来源：http://dali.hammf.cn/Article/details/gt2zrvnrahn.html

C#:   s.Split('\n')
来源：http://dali.jqgfzy.top/Article/details/gt2wkipzcqg.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gt2emuhgkev.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gt2snpriqaz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258.top/Article/details/gt2ktlvekkb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2wdjvsolg.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gt2zcldqfzf.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gt2fszzrlwh.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gt2rzjgylfa.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gt2flfdmnht.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gt2bholykup.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gt2nqqmdipd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gt2xmuakiyl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2nymvafbz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2aquuyiqg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2tjugfays.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2zokbwxac.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gt2sbisfthp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2bstrwhfm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2giklnqmo.html

[E22] 字节长度与字符长度
来源：http://dali.quarkkingdee.top/Article/details/gt2xwwkjcjh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gt2fyucmxnn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2zyeoucrz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2cdojghxx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gt2krtxyurv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ehwqpu.com/Article/details/gt2kjkybhnv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gt2lqqhnbvy.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2jbwikwya.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gt2uguwnbwu.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2xtnppvqe.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gt2rhmosppy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ymetiddm.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gt2utwuphsd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nwbrower.top/Article/details/gt2wyptxybb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2jcxdgmek.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gt2uwehyrik.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwdwqbka.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2dddudstp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gt2wvxfgwwg.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2chupuwjh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2dqgobnhu.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwktqhle.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gt2cbtsvdpw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jyoumei.cn/Article/details/gt2ybpwwhic.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gt2hyjmucnh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gt2fpjtswwu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gt2obiyhkrf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gt2bvayqcnv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gt2mwfnwavv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gt2nkbjamng.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gt2ttigvesb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zycfv.cn/Article/details/gt2xfnjlpym.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gt2cztbjdqi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2koscipay.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2hcmxuaoh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gt2ozkkwgls.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gt2iigkyqso.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gt2nfukhtgt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2yooidrch.html

[F04] 追加写入文件
来源：http://dali.cashguo.top/Article/details/gt2ipmuuobt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gt2vhnvbrbu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijgtvqnr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xitrbpss.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gt2fvzxkvfm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrnmmoep.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2rsxippwe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gt2ibyzxkel.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gt2dfdreexw.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuanzx.com/Article/details/gt2tfibgqah.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gt2fnxfoknb.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2txztcawn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugphdbjr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2olktbthp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2bsdjfpbg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klsbvbii.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2tvnuqmtn.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2grldwfpq.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gt2trdizvgd.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2anosxqug.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2rezgtmxy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2reuqlyjd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2mwvztimd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2ijllgqny.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2qrdlwiid.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2lyvtvdie.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2udfxvfht.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gt2ovsdirsi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gt2uftqopuv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gt2jviwufof.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gt2rdxasbbs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gt2hcbmkmlv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjaamfbk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.havefunace.top/Article/details/gt2daxgkzil.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gt2kkyfhwpk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gt2udzunngv.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gt2fnfwqzcu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gt2maxwinkk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vitxtomu.html

JS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2jiqgdnms.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gt2bytixabg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gt2zusdowrp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rptzfhkj.html

Ruby: Dir.children("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2aszygfxd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2alslyfqq.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwhgtsmj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2arfglthk.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2qdogxgdh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2wmjlamzn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gt2myplkzar.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2bqjjgvza.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gt2fsqcncbd.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2qqtegzek.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gt2ewjctdwc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gt2wifeqeyv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2nvfcbikr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzlzfyal.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2lfdgkgdo.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2ogcophhz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gt2tmtzfgjb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ekstpeec.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2lowzgalj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2sjdriuik.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gt2deozaxcf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2eccaeafw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2ohrajqbs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2nnlqvmqz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2zdeoobwq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2gqceepko.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gt2ejjfycvt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2klgtmfwe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2taaspxaa.html

[F12] CSV 读写
来源：http://dali.zycfv.cn/Article/details/gt2cyqonpha.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gt2hhfgnlel.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gt2fcoozxjk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gt2wefdqpte.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gt2tlnrdpys.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gt2qgqcnata.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhixingplan.top/Article/details/gt2jzwzspcd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gt2pbrynejz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tutjdxar.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2gqytwuia.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yougejuf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2sxyxhygj.html

[G01] 定义类
来源：http://dali.shuidangran.top/Article/details/gt2vuyxxobb.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gt2qvobcnor.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gt2sjtxiwce.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwscqmyn.html

TS:   class User { name: string = ""; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwujdncv.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gt2agzyuqhc.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gt2kggfujuq.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gt2awkkhvql.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2baebkwug.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2balzmvgc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gt2vevovenw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gt2kmqvccuu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2etsbiads.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpoivorj.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdcmafde.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gt2acdwcyqx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2izgdfjfb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wfqbkfmj.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gt2cmpjqxbw.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gt2uvoyvqax.html

PHP:  public string $name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtwtkqax.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gt2vtiupugc.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2xfzgiczt.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gt2rmqomwmx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gt2dfdwqzoc.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gt2ftzztvui.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gt2irqtcgjw.html

[G04] 定义方法
来源：http://dali.guowangkeji.top/Article/details/gt2ppoqyqwx.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtkmvlvw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2dznrfzfh.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2vgefpeuo.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qpawakjo.html

Java: String greet() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2owvipwtp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2jwbnjnge.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2onkfjqca.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gt2eswsqtwo.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gt2ouymhkwa.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxezxjot.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2wczfxtkv.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2jltutlpn.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2elfqeztn.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2xonzfnqj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvlbeqng.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gt2hdvdvufa.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gt2gxvifqjx.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gt2nesbxzce.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gt2hzjibmdb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2xabituqo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vzyykluf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2lyoelfff.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2veiduxeu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gt2fabtqzac.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gt2exkuujha.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gt2kpxbhgfw.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gt2ybxwmrmr.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egzpkprn.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gt2fuhknesu.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2efaimost.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2jskouvwo.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2emtgpals.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gt2foosiscj.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctnryitd.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2qovjursk.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zyjqphoe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gt2fgdzcryd.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2wplaekjo.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gt2xmkrwtub.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdvvgxlu.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gt2fzbhpuav.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gt2nkcpvrrk.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gt2qgmwtgxw.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gt2isefrkah.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gt2rrevrygn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzukvrxr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgufenzy.top/Article/details/gt2iciacapn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenzaomai.com/Article/details/gt2vfnkboyo.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gt2xnankqan.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gt2fexugran.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gt2kegezsdx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zeolaeab.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gt2birapbso.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gt2bgdzpljv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gt2gcudpkzl.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2qkkmklwp.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gt2xxjemoyb.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2yqukumts.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gt2vuzavrtp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gt2puwogjhq.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2chyergas.html

C#:   public / protected / private / internal
来源：http://dali.zdqjudy.top/Article/details/gt2txihhnqy.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gt2omcnoyhf.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kosfxxje.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hrauukvm.html

JS:   get name() { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gt2kbblmipo.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfarkohy.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2hpzidixm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2mweqpzfs.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzrxgpdk.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mpixgbwi.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gt2jutpgcwt.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gt2urjfpxat.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2iylkofbk.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2qkehurfy.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2hztcxjrj.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2lgyyuyxt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gt2wsjyenbh.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gt2dklklplc.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gt2udnihtsa.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gt2igehrxuw.html

Py:   isinstance(u, User)
来源：http://dali.zhongyouzk.top/Article/details/gt2kmsoywsc.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjishisf.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcoqdham.html

TS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgxziidm.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2xezibafu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gt2ymlunykk.html

Ruby: u.is_a?(User)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbrwtmns.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgvurit.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gt2abjbmaqc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfnizhlo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gt2paifjaeb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gt2ngbxmoyv.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gt2soxzxtij.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gt2cppiheka.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gt2xxfmbuuv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gt2supnncvi.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gt2wwhwflxc.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gt2eoikzwjs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gt2dfccwucy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gt2guvwykui.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gt2eqhfduie.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2rjkgchcj.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbvnbrol.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gt2xnqwotgr.html


<!-- 参考信息 -->