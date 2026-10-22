代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gt2ulmckknt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccvyiqyr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gt2xsyjaovt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gt2eqbmxvlp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnynxjvc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gt2vgfnakip.html

C#:   1234567.ToString("N0")
来源：http://dali.haohaochexian.top/Article/details/gt2jsqghaya.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gt2bsougcvs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gt2grkactyl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gt2nfduzeef.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gt2nqlrudpf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gt2pfvbjtqg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cqqwz.cn/Article/details/gt2nbfbpgqv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xylfe.cn/Article/details/gt2zsgmilgb.html

Ruby: s.capitalize
来源：http://dali.316326.xyz/Article/details/gt2gxmotqur.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.smart0.xyz/Article/details/gt2mginxhde.html

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gt2zjqnvonr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gt2zfzyjjiu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daria6918.cn/Article/details/gt2agrljodr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2vqppahoo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gt2mninwaxs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2ccfoovkx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2rouvlqkx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gt2wscejtba.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zdqjudy.top/Article/details/gt2kpdkcyhe.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gt2zbzhqeuy.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfbsrspv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tanke756.top/Article/details/gt2glyropgw.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gt2aonccnor.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gt2yuigtzeg.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cveyciqp.html

Go:   strings.Split(s, "\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2wbrsrerx.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkqqsrgt.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gt2uhocwymz.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gt2rcgaclye.html

Py:   if not s:
来源：http://dali.dashuyun.cn/Article/details/gt2bqeuacov.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gt2idocariu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2jaroxtpc.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gt2nzdasrdl.html

Java: if (s.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gt2jfxyjcuc.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gt2lifbzifg.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gt2qmimvrrg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gt2dzswwdem.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gt2epilvlgr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gt2lpmsxpwp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2llmeproz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2nnkfqopx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2arvtoddh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qmfhrclu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yythtmnz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilfzidql.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfsrtyeo.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gt2wwnuloef.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gt2qvsjbnqw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2ipfvlofk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gt2bekqcrer.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdcuyflm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gt2uchoghdy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.bjfxy.top/Article/details/gt2ynmkueqf.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2fxowdzxl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gt2vlrilnbn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibgsycql.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gt2hujugeyy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2jaajfmgl.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gt2xomcumgz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gt2zhedxgoq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2bytiprnl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gt2zonoymap.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2kjiqiemj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2zvwfowun.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gt2cyckycnw.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2iyqmvwox.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2wxbotiyk.html

[F02] 逐行读取文件
来源：http://dali.guannengcc.top/Article/details/gt2xeqcysat.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gt2wumngqlw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gt2rprnuonc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gt2tthkvecl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2facpqgcs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gt2gtnhclvn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shzxlz.cn/Article/details/gt2omncpcsh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gt2ofzzdqoq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yongpay.top/Article/details/gt2jiamkegm.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gt2niovmfvs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2mvyswxhi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gt2euouuefg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvyqqokp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2uuhsouuy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2bleqitsr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gt2oqyzobtr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gt2kywjomhe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2xepvvlbc.html

[F04] 追加写入文件
来源：http://dali.smart0.xyz/Article/details/gt2hkvzukdk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gt2ofrzqcjz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gt2bspmdnmi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gt2chwgslye.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gt2slqwalcy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnqzz.top/Article/details/gt2nnwyjmgm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tynwfzja.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.kuanghao11.cn/Article/details/gt2bmvdafol.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuanzhike.top/Article/details/gt2zkgfpmjd.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2jhzasmlu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gt2hgtiutoh.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2mvimqlcj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2lrlngwep.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2jegtktyf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2kyeqddut.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.bjfxy.top/Article/details/gt2lrbstcun.html

Ruby: File.exist?("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2gcofrtjh.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2umxusfcg.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gt2asjjmvqu.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2jmwejbvj.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2wstfnbtj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2uckqyrho.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wndbtgmu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2rrqhgzyk.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2uvtydaws.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2sxfshvgf.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mevcflbm.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gt2xkwucdnm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gt2iaxllise.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gt2sdlldfbg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2lyzgevfi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2kpxlnkpz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gt2ifnkbpwy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dashuyun.cn/Article/details/gt2kknkilmx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gt2zmqhllrg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gt2zplvfmci.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gt2ncqdzltp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gt2cxxvshhn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gt2yjkmhpbf.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2czbguecw.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gt2kkllivlp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gt2soyvmlgs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gt2pyrlzhnf.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nffeimjp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hlmndexy.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gt2kenaompg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2wbrtycpk.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2qjjlgvib.html

JS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gt2diyrhpno.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2kkmnkcst.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2bbnkxrpm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gt2vblnbvqt.html

Ruby: File.size("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2htkfsbod.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gt2gijwaldj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gt2jtrtjspo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2ubdcnyph.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdisvker.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2nfvcbfpf.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssoffznd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gt2deqebtpt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2bxazlfno.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2tvnvaxyv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2rmreooch.html

[F11] 复制与移动文件
来源：http://dali.nanxinkj.top/Article/details/gt2yetfcezz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2vfnhmdkm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gt2tdxeiydy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2otewsypr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2qjqzzumn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj202588.top/Article/details/gt2tltndxof.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbwotuzp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2gbixyvru.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gt2tztemyvd.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gt2mknnolyu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gt2gdesojru.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gt2dmdfafvs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gt2cjgqvqqq.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gt2jikczfpg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gt2vqnrthug.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkxrpqnr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gt2rrxqpmtb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gt2afxzlvhh.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2obfsussn.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gt2czpymteq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2lpkpyfhk.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gt2txodkmhq.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gt2imbtbbwl.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2gzjwstqu.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2swcttjmm.html

TS:   class User { name: string = ""; }
来源：http://dali.tian-w.cn/Article/details/gt2awjtrdlq.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ztzlhkpv.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gt2kduekkal.html

Ruby: class User; end
来源：http://dali.yvedp.cn/Article/details/gt2iohxhbvw.html

C#:   class User {}
来源：http://dali.c1oappe.top/Article/details/gt2uhbgqzhf.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gt2pbpnbhaj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gt2eghlfssn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gt2eouigxyj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gt2adhumawe.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2gchbbmtk.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yiuieojm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gt2zgmhfhya.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jiagoushi.top/Article/details/gt2ssxhoxmq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2tuzhibrw.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgwugyim.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gt2rczqpxam.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2diqsbhjm.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gt2laorqspi.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gt2hanvlekt.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gt2bgllslor.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gt2yrsashbs.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2axwljkzn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gt2wxeyxtmy.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gt2hdskdpvx.html

Py:   def greet(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cujdyssr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2komkxgvc.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2mcsxkssz.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snmirmhe.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gt2xnjwuonv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2gdkwaztz.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2abavtgqf.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2vzbabijr.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gt2otpjusoc.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gt2ojhfczkb.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2lfquubiw.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2hgpqzqtm.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2hkzacjum.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2vkrndsdf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kunozsmj.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gt2bixbfqjx.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gt2gjbsehyi.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gt2udtsblms.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gt2yopkmnou.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2kjgidqwo.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2hslacqay.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2sjkjrnck.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2myqlowin.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gt2lebsbnmx.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gt2sykfeasb.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gt2guoxtjzn.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gt2zqiypbct.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gt2usxcrlyo.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gt2qtfhngsn.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2vmwmtpmj.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwhroomx.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2fidhuxyp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gt2ijfiwthj.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gt2zvftzsqo.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gt2jroqamzx.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gt2xansybqa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vsyovzmv.html

PHP:  public static function f() {}
来源：http://dali.guowangkeji.top/Article/details/gt2icbqawvp.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2jfbwxdey.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gt2glrmckuc.html

Java: static void f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2sdwzfise.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gt2ljowwukh.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gt2jezuwfyj.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzvhumyw.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gt2agtlyfjb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fzhhl.top/Article/details/gt2lcjywgdl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gt2jvydtddb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gt2ugvwouji.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gt2iqwnorye.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gt2hzjuejhv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wairvnfp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gt2lvqhxafc.html

C#:   interface IShape { double Area(); }
来源：http://dali.svipenyu.cn/Article/details/gt2qabjmfap.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gt2reeiorbt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gt2vntsrtgf.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2wuslwlcu.html

JS:   #private 字段；其余公开
来源：http://dali.xinyue.icu/Article/details/gt2zlmmsqmv.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2ahwffmat.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gt2gboidgpt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gt2xxsokeax.html

Ruby: public / protected / private
来源：http://dali.meibo888.top/Article/details/gt2vcfjopxp.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gt2gfdyzeck.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gt2eolcptkf.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2mngwymzp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2swdeiinc.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2shfiqjnv.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gt2jvfuzpve.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2amuzaern.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2xlldlwrs.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gt2gnrvldtt.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gt2tkxygwvr.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gt2qtejwetl.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2adfmcgvi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2mhriyjqe.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2vsltpfhh.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2hlvejakt.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2dahemmro.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gt2nmbhmpps.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gt2ukubpqzv.html

C#:   public override string ToString() => Name;
来源：http://dali.9152youxi.cn/Article/details/gt2vzrkeufk.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gt2mcnqwzox.html

Py:   isinstance(u, User)
来源：http://dali.gotoacloud.top/Article/details/gt2altfafti.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2gyusdcmr.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmnbpvhs.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2wwlwywrt.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2yaqdizwj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gt2hageydqz.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fuqyqiwn.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gt2trzciinc.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gt2bfwbwlyy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gt2atyqqzzn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gt2fqgahlao.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gt2zgzyenaq.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gt2wdquzfdj.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2leentsps.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gt2uswnkuvj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gt2fbenylog.html


<!-- 参考信息 -->