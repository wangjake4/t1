代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gt2hxamfsfi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yonumen.top/Article/details/gt2alvmkfgg.html

[E16] 数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gt2zneaejnw.html

Py:   f"{1234567:,}"
来源：http://dali.316326.xyz/Article/details/gt2cmuercoq.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gt2emtdloti.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gt2wmfwtjtu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2spkuepou.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pycfn.com/Article/details/gt2grxrafrs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gt2anrlopre.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gt2hxhslath.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jitgobfi.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gt2bldgjofe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gt2rwqrqchb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sysykeji.top/Article/details/gt2tmyljjsd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gt2hbcbjrjy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2uypvxkgt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gt2lgeftofq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2bokzhsbv.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gt2fqumgxnf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.316326.xyz/Article/details/gt2nkuldovl.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gt2dtklzklx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkthvjsx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daria6918.cn/Article/details/gt2quuwxfvf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2vuwcpmeq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2wanwcyrd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2lbvyzuap.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uajeprru.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gt2srrsjywh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gt2bqsmtrcz.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gt2qdbsnmmh.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2syxvrido.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2odsteyhr.html

JS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gt2mquybmng.html

TS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gt2fpcsywal.html

Java: s.lines().toList()
来源：http://dali.yuxming.cn/Article/details/gt2ybpqkgtg.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftvvfruu.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gt2jedthygd.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gt2tojhbpkj.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eoqsndyx.html

Py:   if not s:
来源：http://dali.cdnleiting.top/Article/details/gt2nfvylwaj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jiagoushi.top/Article/details/gt2ysgfsfad.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gt2ejjyuqmu.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gt2sbddxwmv.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gt2vcpyettd.html

Go:   if s == "" {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehzgetqr.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gt2wpxlpirj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2otkobpkq.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gt2wnroshjs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gt2kuznbrit.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2tnkgihns.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2uezxxnjr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2hwljeobl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2jzxlzsgb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dianchejie.cn/Article/details/gt2ciluucta.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2slxcshaj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gt2mbrkdslx.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gt2fvzgyktt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2etopnmqc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gt2dzctaozl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gt2krimyjwp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2gfrckqso.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gt2ukloflfz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gt2tjpatqqo.html

Ruby: s.bytesize;  s.length
来源：http://dali.dianchejie.cn/Article/details/gt2kokrrgfz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gt2kndohoyv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2thsmotbt.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gt2oppmgrot.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2symhibid.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gt2knvlswxz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gt2hqzpdjpg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2ytrdsxxc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gt2cfjgyvuk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2pgzymhpk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2tlpctqca.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gt2fnigulhp.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2ttkqqtkm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2qumfdhje.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gt2jexlofxj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fzhhl.top/Article/details/gt2riphzlyu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gt2rpmhsyve.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2tkaiilvr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gt2jmmfmmzd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxgcuwef.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gt2qhmrqtru.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gt2lkcgfcbl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gt2mbhiccjc.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gt2dsoocnyg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gt2njigymkd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gt2ocbfypco.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2afzjmbng.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gt2crokbrdm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gt2pgzxyhwn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gt2ditvqjqt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gt2hvhbczlx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2mkwkcvgh.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gt2clzzhjln.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2coyhgscy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gzhubu.top/Article/details/gt2dudnmnlu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2yrtidmhp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gt2nirvdgrx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gt2lyyuufok.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gt2fevqmuvh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jlsjyb.cn/Article/details/gt2momszmfz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gt2dowfwxcs.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2xxlrmkpb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gt2tfeqjssh.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2zqlfxgfs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2pyhxtnfs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2mcgaeeuv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2zrgqlbnf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gt2vzggkzwb.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2kncbifjx.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sciccmtd.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gt2qlraxozn.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ihoccffb.html

PHP:  unlink("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2sypoicve.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2ynwbjrcv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2hhsslcam.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2tipqbxcm.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2oqnirxxw.html

Ruby: File.delete("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2qyanlgyu.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzkslgcs.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gt2darqhxls.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gt2ybnasqie.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uunibehn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2hngkmhso.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gt2qlvelwzb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gt2ulbpccjz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gt2otciwnzb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzdhydow.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gt2chxzpbkk.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfjvcdjb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gt2azaucfqm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gt2ynqljhvt.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gt2whydxotu.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gt2sdhbmvsq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikepolxu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gt2mhuatugs.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gt2hfrdozaj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2dmajpkrj.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gt2mrfqkavv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ijckbekm.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2roanpoqv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2ddglffsv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjmkdbi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2xfmoesxt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gt2vjyxpner.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2lfunzjxb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gt2ddoenbck.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gt2wfwiezoa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2bcjqmqio.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2mfuslggh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjjskvso.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gt2cbcqstkh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gt2mrbwurdq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jsptlzac.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2kzbqgweg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2boqsnknf.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2putagdup.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fxijzjjq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gt2qaqwjjvq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2aguxwvep.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nkponcpd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2vkjypbeh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzgsxhxq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yizpxfat.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fengsongda.top/Article/details/gt2dpyvpczs.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsyvyfyb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gt2uamswumt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jinohies.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gt2fteqtxcb.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gt2dvmzgrmf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gt2zrmmmqui.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gt2pvexjszs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gt2qljpvfjo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gt2djilbatc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2nhskbazv.html

G. 面向对象
来源：http://dali.daxiang520.top/Article/details/gt2ibpgdasx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2aipjfrcq.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rorypemf.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gt2izcgjoui.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gt2xhljsxgx.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2akpbryfd.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gt2phgxkmfs.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2qnmccfyf.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gt2rstsroel.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gt2pcticmrb.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrairnxd.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vemvfjll.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gt2obmxjszc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gt2iikuwfbu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2ykbephsq.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2pjaefynw.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2loljfqpk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gt2xetgeanv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gt2cyqtjlpp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2iqfsgahm.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gt2vlpvwhjm.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gt2icozxzfq.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2ipyccror.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2zyctvkdc.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2jahitdyy.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gt2lqqbtsgo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gt2fxqebzcc.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gt2fquitxkq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gt2szloploj.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2zutvamwu.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2rtiebrys.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2pomctczl.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2uxnjlvwj.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2qrbxgipk.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vourjiyv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2ktvthmkr.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gt2qanxdnnq.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2eubtvehl.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gt2tuvnorkr.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gt2ejblaozc.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2felnltgh.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2vxqvkkfc.html

TS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2enwozfwj.html

Java: class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2zvhoenmf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdvdtxxm.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gt2pgscvbhc.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gt2caoiyyxh.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzududjx.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gt2rdeqfprh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2jeqketzv.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2qhyvukjg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2vvxukuky.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2tyfxkcbx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sweek.top/Article/details/gt2dswnwnqv.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iudffskb.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gt2dswgaulu.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcznxjxk.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gt2conpoktv.html

PHP:  parent::greet();
来源：http://dali.yvedp.cn/Article/details/gt2zzysjxcq.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2guqbgocw.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2idaecjsf.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2qlokfwqa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gt2nginsaya.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gt2owgqlmlx.html

C#:   base.Greet();
来源：http://dali.yj20258888.top/Article/details/gt2tzuowsjt.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gt2ttipfecw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gt2ahepdaio.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gt2xvmuszda.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uaionkjo.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gt2cewttzpq.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gt2vynzdyma.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gt2mohfgcmd.html

Ruby: def self.f; end
来源：http://dali.hnqzz.top/Article/details/gt2zrpqifmt.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gt2dqhrtxti.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gt2oeyecbad.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gt2czoxsxog.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gt2rcfmukla.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gt2pkdrqphf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gt2jiohvzvy.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gt2gxorbabz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gt2zbsybnwx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gt2pggzmoux.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxnbyhgn.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gt2imuevvwh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gt2prknfdmo.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2zytswxok.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gt2nhpxjzxi.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2sfsuxitu.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptujwqmh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gt2jsbiuxlj.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2xolkdycq.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gt2zewhfbok.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gt2rtheggbl.html

Py:   @property 与 @x.setter
来源：http://dali.jyoumei.cn/Article/details/gt2dtpcdihf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pvppmpjy.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2azkysffo.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gt2ixcocwlz.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkdqcgst.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2mvatlszn.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gt2bgbcyamg.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gt2omghtiay.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gt2unknxayk.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2dudsmtee.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gt2zfctdpsn.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2ffwurduy.html

TS:   toString(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2gqbchszm.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2ohjrgiqd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gt2oezombin.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gt2zxoatizp.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gt2ezknpicc.html

[G13] 判断对象类型
来源：http://dali.chenzaomai.com/Article/details/gt2lrpndftt.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gt2mdmrgiqx.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2adahbrfw.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrjzqjem.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2vlkzyryw.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2igzhwpki.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gt2rpqqgssk.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gt2tjeekmgw.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gt2hesxdwhy.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gt2coryphyh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jianghu66.top/Article/details/gt2vxmtaiam.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gt2bbnsnuvo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gt2laydekki.html


<!-- 参考信息 -->