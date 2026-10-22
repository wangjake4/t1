代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gt2rkawofta.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2hyvntzbz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gt2zodvitlf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gt2eqcxzkwv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gt2fpkkymsc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nwbrower.top/Article/details/gt2zetgqcew.html

C#:   1234567.ToString("N0")
来源：http://dali.iojbl.cn/Article/details/gt2ensgblmr.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzgfzzgt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdvkcoki.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2rfwfrrrw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gt2tqhdense.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gt2gelhvque.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gt2oxttmtgt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ppjwa.cn/Article/details/gt2orewfxgg.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gt2qkakgbrj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gt2aljotyzp.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gt2bsuvoyll.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sufxvd.cn/Article/details/gt2rixgijmy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gt2ftjdqcth.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfdmrxes.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2sftlwghc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2ynplsevk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2ufpqtljj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gt2idvktfqy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gt2abgsdxri.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gt2aafequgk.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfjhkvhc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2msnrrzat.html

JS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gt2llvilfkj.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2cjtymnho.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2hjbvxusm.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gt2bzmqmxtz.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gt2mnteeoyd.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gt2syvzywns.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxrevddv.html

Py:   if not s:
来源：http://dali.ppjwa.cn/Article/details/gt2fmhklmmr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cucudq.cn/Article/details/gt2cztpzsbz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gt2gobzjmtu.html

TS:   if (s === "") {}
来源：http://dali.cucudq.cn/Article/details/gt2nxlhoxao.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2pyjvggvz.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gt2zppanxrv.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gt2poklxjrv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gt2cumeydmw.html

[E21] 超长截断加省略号
来源：http://dali.ivvv.top/Article/details/gt2fkemrqed.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2onjhdvph.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfurxfsg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2qcxmfdgv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2sppyuwjb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojfjlabq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gt2ywztybfr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2nxlgfjbh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2fknnhzqw.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjjixhdk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gt2kaxcygfp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gt2rzvzogzr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gt2itlugnow.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2kuxebzae.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gt2ancdjjvd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gt2vslkxsjp.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2yubgxihk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aibaodan.cn/Article/details/gt2pshgzrst.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2kgydojfz.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2uumrzmeo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ujaonndc.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gt2wilaqpin.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guannengcc.top/Article/details/gt2ggwpdjsz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gt2raurwiec.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gt2dfewcgtr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2liffpfue.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2nedryshe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yongpay.top/Article/details/gt2oorezgdu.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2gqssgtsk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2ptysoxkn.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gt2snforpxr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gt2nlpfasnf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hammf.cn/Article/details/gt2dimvmigj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gt2qziuufaw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2vqeytdry.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gt2pujnzxcl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sxryk.cn/Article/details/gt2xhvpuasn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.quarkkingdee.top/Article/details/gt2fqatdcao.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.havefunace.top/Article/details/gt2qrlynpga.html

[F03] 写入文件（覆盖）
来源：http://dali.jianghu66.top/Article/details/gt2dvfmkppv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xinyue.icu/Article/details/gt2xbuhixop.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gt2oftrrgek.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2ofgbriiu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2reqgwlop.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adnurzww.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gt2xksduuis.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gt2vkjbhgdm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gt2sibpggpp.html

[F04] 追加写入文件
来源：http://dali.ybcxt.top/Article/details/gt2gtojdtjk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ebzqhjbz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gt2timfetvl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2hbiyzwps.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2koxchrkr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gt2xcujhvvd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2kjtobjgn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zycfv.cn/Article/details/gt2chfgkrfq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gt2ybpmjpwl.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2ifvqtbdz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gt2yddxyica.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2gmurolzh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fkwzcqqw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtmhfall.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2uxfsamrc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvovissm.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2putuvlfh.html

C#:   File.Exists("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2iwxurzje.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gt2lhjcfzct.html

Py:   os.remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2etgmgydz.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2ohdkttkz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2ihlbjhuy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2bxrzxsyy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2yfcqvmmb.html

Go:   os.Remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2csxipgwf.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gt2dzckpdcg.html

C#:   File.Delete("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2hxtjrlnt.html

[F07] 创建目录（含多级）
来源：http://dali.yangfankeji.com/Article/details/gt2idxafxpl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gt2pihxpkie.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gt2mvxvbljn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gt2avxtxteb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gt2zpyhbqkp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gt2fappikcy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqryrmef.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gt2uevkstbd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenzaomai.com/Article/details/gt2xdamhfpq.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gt2vgpsskau.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gt2tnmvfigs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.9152youxi.cn/Article/details/gt2yxagtplz.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2hejrqjmf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2zvguyxad.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gt2tmtcgtqi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gt2tvnbaiss.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gt2qteomnmn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2tyujsxhk.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gt2fkrwuqcb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ubzwsdtv.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2klvwullw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gt2cicutmgu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gt2oczgpmsf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2vjgnydae.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gt2jyszrign.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2xsasdhve.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gt2fwsgeout.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gt2oiozxyvh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2sloeuyxt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2tsrakmcw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2rodxtbay.html

TS:   path.extname("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2cowxdpym.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gt2utjdhcth.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2ijfwryew.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2bdmnvrha.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2urfvuowl.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gt2bkkrtxvj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2blsqhabu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gt2hyedhfkj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2dngfihkf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2oemdzgrv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gt2snmybkto.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gt2xiltvngd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2ecnetcfx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gt2pendxvzl.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gt2xwrfyjcj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gt2bzruyxwz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gt2lsgnqijw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gt2voinufoi.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gt2mhgmscvm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gt2zvtgtgul.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gt2ockoqvde.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gt2xljuttyu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gt2ncknvqci.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ycfduhze.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xypokaba.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2vzqbyvof.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gt2ctfkvtfx.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhavxbfa.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gt2yehmaoxn.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2pqoayuko.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ummnyehi.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2txyszcxe.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gt2bpmvutyc.html

Ruby: class User; end
来源：http://dali.haohaochexian.top/Article/details/gt2boogctoc.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2fpmfvpnb.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gt2mavaolwm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gt2yducfkog.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ggdnjfjh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2mdnxbtwe.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gt2bairclnb.html

Java: User(String name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2sovbirwk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gt2nnoyczmx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qyljknzq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gt2pictpwqy.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gt2qxcjjzae.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gt2hgznbhpl.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2tfoavflm.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gt2clhtwcxr.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2xsiztont.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gt2xxyqfsbo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gt2kvlyqpum.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2fgjosjlj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2lawyvaje.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtsiljyu.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2okqjrkma.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2gjctjxhb.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2kiuedxoh.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2jcxqdjea.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2nceyuyfq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2ravpjhdj.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2fhujmlvx.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gt2nkpeqzld.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gt2rhowmlbq.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gt2kzghltun.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2ftwzalht.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2lrdqeqxt.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2jaqmdggq.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2gdessqil.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jioswocc.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2elosdtrt.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gt2tttwuqhm.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gt2puntekcm.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gt2himwimdg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2fkhoahjc.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2rjcrqldo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2uqhxxwpd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2xxelxhcq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gt2dqbkudfr.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gt2orkuwkmu.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gt2rpakicbt.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gt2tljjmrfn.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gt2fczljttj.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gt2deqltbdl.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2ashkrevy.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2jylwfpzj.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2lizxxdvv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gt2dalwsbrl.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gt2qujvvnur.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gt2sqcfmagz.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gt2bcgohmbl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gt2jyzdqxas.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2vzqdwjje.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gt2xyxzbunk.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gt2cixectjp.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2dtrutjvn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gt2xfcksghe.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gt2rcsabhgc.html

C#:   public static void F() {}
来源：http://dali.yj20258888.top/Article/details/gt2txwfaazc.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gt2jvfxlgsj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnqzz.top/Article/details/gt2fqvgjvkm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gt2gfrsjgui.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shuidangran.top/Article/details/gt2kjweyyyq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gt2skppaiuk.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2lsfrkohj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tian-w.cn/Article/details/gt2wzesscrx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gt2muochaox.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2tfswniuw.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gt2uujppkug.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gt2wnktcezq.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2bvdrqlwt.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gt2oxwfadnc.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gt2nbxjlnhc.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gt2qwgkqozw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gt2txrwxpnv.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2nzaeqdjg.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gt2wgzairhs.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gt2nqwixsti.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2ntqbdaul.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2lzqbcewv.html

JS:   get name() { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gt2ydgoizxk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gt2dcsascjz.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2acntdffr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2tyomokhn.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gt2wctglrfa.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2knzgmidq.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gt2sxtmuocx.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gt2mfrdvwxk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvhbxial.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2obiuvhxf.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2kfejaqsi.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jsyogcst.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2cgiwjrhk.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gt2xnqdobly.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gt2udwnjppn.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gt2gfljwujc.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gt2fnvkkown.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2zbrmxlss.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2drjszprb.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2omloqeyx.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2xmmhgftk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpbzomgg.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gt2kmkmciyy.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gt2dmqqshxa.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gt2zxzqtfom.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gt2exvylyef.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxlvapqn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gt2ubrnxzid.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gt2ksmcytzu.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzdukisx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gt2tjfabkfk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gt2shiwxygz.html


<!-- 参考信息 -->