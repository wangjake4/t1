代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gt2qhbxxuih.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gt2coqoyzou.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ufeyqbwe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gt2yqbqicwu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.kuanghao11.cn/Article/details/gt2dfbbmdgk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gt2tynxoftx.html

C#:   1234567.ToString("N0")
来源：http://dali.zhixingplan.top/Article/details/gt2agwjecnp.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gt2otjuatjn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gt2iqdxphqm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258888.top/Article/details/gt2upadziuu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gt2llmkwvmb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gt2nwlxwcjb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gt2nqdudkaq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2rmghbonu.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gt2xfdfiduc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clbiiacf.html

[E18] 模板占位符替换
来源：http://dali.tianlin.xyz/Article/details/gt2hieftqll.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gt2ghtanxby.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gt2fkjtqnwu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2heawljgt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2yunyjuzu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2nexaufkv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2zqdpjfie.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gt2dsiroabq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gt2nhvupekd.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gt2mlmalnry.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gt2hfnwhojz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2kvwclada.html

JS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gt2mfmwkqwk.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gt2zdqemmjz.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2ybgbzxas.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gt2uovdkdcc.html

Ruby: s.lines
来源：http://dali.yangfankeji.com/Article/details/gt2svoljuon.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gt2qfijvrfz.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gt2xqlyhxsy.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gt2kyblodvx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gt2iulmjqbz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gt2qgonxrgf.html

TS:   if (s === "") {}
来源：http://dali.xziqi.cn/Article/details/gt2xtqrbdbr.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2xylwclrc.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xccpnspe.html

Ruby: if s.empty?
来源：http://dali.fzhhl.top/Article/details/gt2cxtdewxg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gt2zerdcaec.html

[E21] 超长截断加省略号
来源：http://dali.pengpengdd.cyou/Article/details/gt2zippkito.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gt2mtxbkpyt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2uoxufhmn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2wwofuhxe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2dfezdxil.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2uicnepno.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgufenzy.top/Article/details/gt2khrvoife.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2ojfcfrwt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2bgwaihoo.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gt2hasdhuvb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qscojnep.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2opjdmtaf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2mowqzydp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2ocfblokf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gt2fvcqlstb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gt2zvdimqdc.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2dpsezynj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2qjdcvtdf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2pjhjfjmf.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gt2lrodkydy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2phlpggvh.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gt2yxxlyrre.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gt2yvhwvjov.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2qgcmrczf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gt2yfozmcbz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2tosnxbyl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2wwkyksqa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gt2dpqzxbnn.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2wxcuoucu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2xjeeardo.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gt2mgripbhb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gt2lpgowdgz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gt2ypghodxt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gt2rlbaokzu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gt2wbnnkeva.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxvpsuzw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gt2qapwmprw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gt2wqjpllhh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gt2dvckezgk.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gt2hzzkiuwf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gt2pawsmkci.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2hgfzbeoj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2roustdyr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwsurjxh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gt2hvajzfth.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gt2qizfposc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvvkprvw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gt2voyjouyo.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gt2sypjzovb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gt2rlkjpums.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aibaodan.cn/Article/details/gt2wxehudfj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2cyawatcv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gt2pnigjlab.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gt2riuwgbwt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gt2swsgwsmw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cdnleiting.top/Article/details/gt2jnklshvs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gt2pxfqasnb.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2xonkckcp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gt2msplzfbw.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2tyjzowvx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2zbnrxoyz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2zthgcstk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2ipwbljtn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gt2osytuhdn.html

Ruby: File.exist?("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2wrjztcnx.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2amoidtru.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gt2ixszywqd.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wkcoswao.html

PHP:  unlink("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgzsspph.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2muyernrv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2rptqdpfq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2lvvweqhg.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2dkndqzyv.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2whkcwzym.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2qbthxcur.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gt2xaeqahcm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gt2qnautjoe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sysykeji.top/Article/details/gt2cbkvueeh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gt2azabgelc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gt2pvkvcwby.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gt2fvuxxrkg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gt2mtabzlqm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnxiangtu.top/Article/details/gt2hnpgnctf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gt2kgxmdcpx.html

[F08] 遍历目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2eragrfji.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gt2wiixfnuy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gt2uzqlpfjf.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gt2jfggdqsg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gt2nzpecoxw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gt2jdpqfcws.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2gmyhnsrn.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqrxzdm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gt2qdrumodg.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gt2locepyzc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2xxgmdcez.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2vkiyamxp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tuanfltx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gt2unavkuut.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2yqqoddps.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gt2mpgmtrzp.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cegadxsv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gt2ddwowmwg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gt2mqziifjb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2xyynjett.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2coyheert.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2rqcgzrus.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2yloxecan.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gt2qvchlcsd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2aisioqkp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2imvtqefi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2bgrtumpw.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gt2vmbdutpr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2aboibcqo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2juwvbius.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2arqtatns.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkyaszvp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2anizfreh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gt2zshnsvlp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2llkgiscn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2niizkegw.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gt2pjfpcddd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258888.top/Article/details/gt2rewtsvcd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lphxrpvf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gt2hqqroveh.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gt2faloxefq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdwqexdm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gt2qxlgjkfl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gt2vkoqnhdh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gt2dqwnepen.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2auvfsvbq.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gt2vosqcqqr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2mmozriqk.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gt2umidcywj.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gt2vinuwdin.html

PHP:  class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aimdriiz.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2sonopjrr.html

TS:   class User { name: string = ""; }
来源：http://dali.c1oappe.top/Article/details/gt2sczlprqr.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gt2uuoslnzn.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gt2qfeftzbe.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gt2ghepcxpe.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clsyckzn.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gt2ftietelt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gt2bmdzvlgg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gt2sjthjehh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2xabjjwrr.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gt2scdhyfgs.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gt2zmxelufx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gt2ucackznw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gt2bxpevgjx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2jhbqjdoi.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gt2urjryitt.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2zacwjjhu.html

PHP:  public string $name = "x";
来源：http://dali.sxryk.cn/Article/details/gt2rsjfhqin.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2wlilmzla.html

TS:   name: string = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kuduqxmu.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gt2mqjotxej.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gt2sjyxeejk.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gt2bktpumyt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gt2ypiajvyu.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gt2vlxbpcha.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gt2enxfyqdy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2okyuaugg.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2lywbpktg.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2phxhftus.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2jesgxqwi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2znayhaba.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2ntwvvdsf.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2xopaskxu.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gt2dpwltcfo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbthpik.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2cckuzaie.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2sxberazv.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ecvpmicx.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2fsdamrhq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gt2nxulqwsa.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gt2vgbqwumq.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2meqpprla.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gt2hppchcvn.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gt2bqvfzsdl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fhywyybt.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2pdkdbcxs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2vxhcypxd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2ryihrbam.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gt2vnnqshwc.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hltlgapw.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gt2vvrmqvwj.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gt2jfvwpbko.html

Py:   super().greet()
来源：http://dali.yonumen.top/Article/details/gt2xakdogju.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gt2wrdzslpi.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gt2bzzjbxwy.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gt2dwwaggxi.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2yaoxvyzh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gt2wilwgqpw.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gt2srrsfaqi.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gt2tsqjnkvp.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gt2krqpwzjl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gt2xvbshiwg.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gt2tdnxyoja.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2prnkecnd.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gt2wnmelqbj.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdupwgab.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gt2nfnlijvt.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gt2pamalpkm.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gt2dunxjxvm.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gt2eynuhuxq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gt2xklwhpur.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gt2ufyaugqp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gt2fczdvfke.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gt2silsxlmx.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xcdnallk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gt2kuzrezsd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gt2cnrqwnma.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2efycjpbr.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gt2emcbflxw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gocpdvch.html

PHP:  public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2xbsprcqy.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gt2eojukxce.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2lvmpbzcn.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqvkapqo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gt2qnvkabcz.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2tabdymgz.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gt2vibplbln.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gt2vxzqzbla.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gt2togvaqtt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2stloofbd.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwfanude.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gt2ngprprhk.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2sxlugarc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2tdvjdimg.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dycoynva.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gt2iktdphpq.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gt2xbgnjkuf.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gt2awtooeck.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2ejtnjjej.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2hvswyjhq.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fsuvhmow.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2cvrjtpte.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2byvtdyqn.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gt2xesoolxl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gt2frvolvpo.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfaifwsl.html

Py:   isinstance(u, User)
来源：http://dali.yj20258888.top/Article/details/gt2ospkvbjq.html

PHP:  $u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2krorsjyq.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2fllccsmr.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2otprsnia.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2xublqwae.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenzaomai.com/Article/details/gt2odfqalvx.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gt2frvciikk.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gt2iehohpvl.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gt2axfwkdif.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gt2ghtwmfdc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcvtwbib.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gt2bdfkjsci.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gt2nxizqhbq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2keyrltvj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkdvkgtb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujmpakgn.html


<!-- 参考信息 -->