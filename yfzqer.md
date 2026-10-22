代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenzaomai.com/Article/details/gt2aadqxazq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zycfv.cn/Article/details/gt2acszqxfo.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gt2jfixjmxu.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkjvdfnh.html

PHP:  number_format(1234567);
来源：http://dali.chenzaomai.com/Article/details/gt2wiqvnbok.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gt2zbdpfdrp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gt2wlslrhdn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.smart0.xyz/Article/details/gt2nmbzkpet.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gt2jyiebtxd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2oqcnhmba.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gt2scdehfef.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gt2ansubylb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gt2zvjvxqwy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gt2fibxxxtm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2hvwzeuog.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gt2ubgzrjll.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2crffzyxz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gt2ggbildyp.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gt2bzyzatig.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gt2tcozxzon.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gt2wylnyyuv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gt2lwkenvpx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gt2jrpkiyzh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ofzbxwqv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2hpstrfyi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2inweihmv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2fuludftm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cdnleiting.top/Article/details/gt2senyxlzw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gt2igeeakye.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gt2ubtovkmf.html

Py:   s.splitlines()
来源：http://dali.wangdashe.top/Article/details/gt2cblrauaq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2yzaiuqmi.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zpnzcjfv.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gt2kseawohu.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gt2tijhcsvd.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ylcokgdj.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gt2cmycivhe.html

C#:   s.Split('\n')
来源：http://dali.dashuyun.cn/Article/details/gt2fjgvcyaf.html

[E20] 判断字符串是否为空
来源：http://dali.andypj.xyz/Article/details/gt2epswlfnv.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gt2vbrvmeff.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnqzz.top/Article/details/gt2uauusakp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gt2uvxfogvi.html

TS:   if (s === "") {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmaybtnv.html

Java: if (s.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jbcdteph.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gt2iighgcip.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gt2cqjuajks.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gt2fjembntg.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gt2dguxelgl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gt2kohcuhov.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2fuwoleds.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2iylzdcdv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2lsyctmxg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2rxocavdk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gt2vuqaejib.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2zsxbytvu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2odrimbok.html

[E22] 字节长度与字符长度
来源：http://dali.yj202588.top/Article/details/gt2jhlrbmoh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cuusoyew.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2txcssknd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gt2aetdmbdu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gt2mdmhxgms.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gt2wzluzmdy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gt2uibutnkm.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gt2ywzabqsb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2krymwdrm.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2emtfiayx.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gt2xpcvbhll.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2cvavpkjd.html

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gt2mannfbld.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gt2ozussrzs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2pczuocpw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gt2rvezfxxc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2qzppqhsf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2coxoszwu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gt2eeusaetl.html

Ruby: File.read("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2ismaotyu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jipmejvu.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gt2hxvixrkk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fengsongda.top/Article/details/gt2axwfqkcc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gt2oylryjfs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2caxkflrr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gt2nvthulqy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gt2yongymja.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shzxlz.cn/Article/details/gt2powwcodg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ivvv.top/Article/details/gt2htuefuzs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yongpay.top/Article/details/gt2tcazoyvq.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gt2vgftltym.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dianchejie.cn/Article/details/gt2umsajvvl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqryvian.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gt2eouqrpyr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gt2krvfjhrf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2egnuhkly.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gt2yfillekh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gt2kraciucf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gt2exrrxtqe.html

[F04] 追加写入文件
来源：http://dali.yanxiufei.cn/Article/details/gt2euwygqpc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2styxsylg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangdashe.top/Article/details/gt2vaaovqox.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gt2qtehcmyg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gt2yuyzaevj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gt2syukoaqk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2obanrlfz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gt2qqjhdanh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgpknhee.html

[F05] 判断文件或目录是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irwidavp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gt2nqrrrzrn.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2urxtrdcl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2gsztsnmd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2rkrvicxn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2awolzugy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gt2gztzgefz.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2atpxglfw.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnzedzqe.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gt2gydpswnz.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2bnpyfchg.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsezhdkn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2shidkgzs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2mneagfvw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2rmfwcxob.html

Go:   os.Remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2eosabunl.html

Ruby: File.delete("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2fmvwvmus.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2duyeellq.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gt2wiagdoxg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gt2sccrqijy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gt2rfzzlzul.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gt2ubstfbtd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gt2mdnccttu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2smdksirw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gt2rhuhuasu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gt2mpnoxwkf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gt2lztplqwe.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwlgrvvy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gt2xeblqpev.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gt2jetsgvyn.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gt2hnnzdxdf.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmsxdirf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gt2ibdnlbjm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2vecdkiyl.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gt2cvqwdaqh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gt2elvlwnsl.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gt2byorwjrr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2jrgcshwn.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2spgykhwy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gt2awcvmmca.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhmoarag.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xanxayrc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gt2mxlvzdbu.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2mlovrqew.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gt2zmezhsqn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gt2euoostez.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2fgtcqogn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2gzptiswr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2cjalebvu.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2khbakzfr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gt2ufrfqlku.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2ijvyxmrb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2jhmcnshw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2fhrldjco.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gt2uqylaaba.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2utrdrkdq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcofksif.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2odsxongx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2bxggznxb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2qrpilmer.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gt2fltotafa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwemrqdm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gt2erkhwjkr.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gt2cplebpet.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gt2kukkvffd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gt2fdlkwrrz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gt2iprjsdpp.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gt2obgmezna.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gt2oebfofgz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.vqdsnc.cn/Article/details/gt2lribmtyx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gt2scjeeoam.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gt2wlofmdat.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2mizgzqdd.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gt2pcupsigb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ynnoniyy.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gt2oesssumo.html

Py:   class User: pass
来源：http://dali.hfpthk.cn/Article/details/gt2slrvjlaq.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2rnbvgemf.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2njzndgct.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gt2wzwmfbcs.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2xdscqqwa.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gt2clhihhwi.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gt2pktkyaqy.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gt2ybfnbywk.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2kmcivqnh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gt2iiwzuhot.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuxming.cn/Article/details/gt2mpvospqb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2xiyvgmvf.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gt2jqdksjmu.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2lscdxcim.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gt2uopokisa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2bkyctley.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xinyue.icu/Article/details/gt2xsqrcjqd.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gt2bdebnkmo.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gt2tdtrnqvb.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2dqpzfvhd.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2hsnkaztw.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhedhbgi.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gt2qxyrgtwt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gt2sfqjgkoy.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2xgqbmzpq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gt2jhjphsvj.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gt2qrzyoxzc.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nxvhbjjx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2gtmxkppd.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2kpwaervj.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2tojwlpqe.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2qgljncou.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2nahpbrgs.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gt2ecylrcve.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gt2fwlturuv.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gt2nccpehgc.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2sufcwixc.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2qtgrumqe.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2tqxpngut.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2acentxio.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2hqefjynp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wozqcgol.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gt2wkggdmdt.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gt2xxobgcvh.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gt2egbnugit.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gt2feraqhkh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twlldejx.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2divdbnci.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2alfzoeef.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2douszpiu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gt2vfgenian.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gt2ijosqjer.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gt2uoybqbwb.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gt2lwhbizdy.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gt2bofkzcvl.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gt2dvsaqmxt.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gt2yzaaaosa.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2izidwqle.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2xclbhvci.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gt2fvdlpjov.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gt2okwugrlf.html

C#:   base.Greet();
来源：http://dali.redwolf501.top/Article/details/gt2jwvkbyzu.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gt2ljlljdlp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gt2cmkxrgsc.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gt2ktexrisk.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2gjyzsbmc.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gt2zftincss.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gt2whtjajov.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gt2mtoumlvf.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gt2bipqxnay.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2optojkbl.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gt2yigrtfcs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gt2rpeupauf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gt2lmgkkpcf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gt2gghziwui.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gt2nhsmzwgy.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2nixdezmy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gt2uwzegiqa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gt2igsqthhi.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2rnokpmqq.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gt2ahjoejzz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gt2ifnsirsg.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2jgwfwooy.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gt2njsjkycg.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2gptnzqia.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gt2xmqvgfzh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lferofmr.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2fejwafio.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gt2frzkexub.html

[G11] getter / setter
来源：http://dali.nwbrower.top/Article/details/gt2frctyvjy.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gt2tcqsgeiq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2kdqobwdp.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ovycajua.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gt2dsavdvcm.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2hievqfyz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2qdxkvntd.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gt2afgzmilo.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gt2mfeszdmx.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2beakmigs.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gt2kitonfoe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gfhukowf.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2vhgqxdml.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2wwhubjow.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2rdrfvqmq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2omcuijnv.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gt2lybqeosw.html

C#:   public override string ToString() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvnplotl.html

[G13] 判断对象类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbvxyfhk.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxucyopo.html

PHP:  $u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2gofpujmb.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2onmrwnbd.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2mzeuqqsr.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2tctacuph.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gt2rittxyfw.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gt2pbpegmzt.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gt2ojqyxuzy.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctcvdvhj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgakzyaw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuanzhike.top/Article/details/gt2jtgjwyeq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxuanxn.top/Article/details/gt2chfvqxup.html


<!-- 参考信息 -->