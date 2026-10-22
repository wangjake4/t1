代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenzaomai.com/Article/details/gt2vaolexjn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gt2fpviyemr.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gt2zmlsfmhb.html

Py:   f"{1234567:,}"
来源：http://dali.nwbrower.top/Article/details/gt2vfgzzgzn.html

PHP:  number_format(1234567);
来源：http://dali.jyoumei.cn/Article/details/gt2ynagzqha.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gt2iwquznhl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2usssqnho.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gt2viyzstho.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gt2zlfbinsz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2cazrjoie.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gt2kpblttkj.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gt2ilnqhcfh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yongpay.top/Article/details/gt2tophgcdf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2thoiokib.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gt2oftkahmj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gt2jreopibp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gt2earzfgdj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gt2epuiqbsq.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lakpjbcl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgfzy.top/Article/details/gt2purhuuwo.html

[E18] 模板占位符替换
来源：http://dali.svipenyu.cn/Article/details/gt2cghshpjf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gt2ahtgiwjj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gt2dwmietjd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2vsqvbbpx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2axczgljl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2ehrqzsvl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjunoqvm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gt2pjtvqbfw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gt2qmdwjfxh.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gt2gotcnsoo.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gt2svmzckxa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258.top/Article/details/gt2hcgotndn.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gt2kbxocfgh.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gt2hjerjgkn.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gt2nfbcchje.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gt2fpgotyoq.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gt2sngujgnq.html

C#:   s.Split('\n')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2raezqsks.html

[E20] 判断字符串是否为空
来源：http://dali.jianghu66.top/Article/details/gt2pqjniybs.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gt2gslomkry.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gt2xnbxhxjq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fengsongda.top/Article/details/gt2xwjidydz.html

TS:   if (s === "") {}
来源：http://dali.zdqjudy.top/Article/details/gt2sxlkhwkg.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2yjvpehbp.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gt2iaxyuico.html

Ruby: if s.empty?
来源：http://dali.bjfxy.top/Article/details/gt2gwjwugaj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2pdwvtmoy.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gt2jdotwfrk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwzogiht.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gt2zksipvnq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2yzvdsmyh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2aadfvhol.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2ccnhmprk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gt2mplaykuj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2qvgxlded.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2enchwuxs.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gt2uiajcthv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zdqjudy.top/Article/details/gt2dvuvhbql.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eckmcedp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gt2siyujyjo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gt2hewspxvb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gt2jmcltsnf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gt2drviqyvd.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2mjosfmsc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gt2vfokzjey.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2wtyhlnme.html

F. 文件与目录
来源：http://dali.9152youxi.cn/Article/details/gt2zulmttoe.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2iqgrpdyc.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gt2nsnkbqaq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gt2ckvnzeqz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2tksavivx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gt2urquxpnz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2gtbzymvj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzcyfsyn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gt2hmbtksbq.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2dadwftdw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2wmlajrgv.html

[F02] 逐行读取文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwdzyrtm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gt2jmftfzob.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gt2bgpmphax.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gt2loiykhcl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gt2tzseispr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gt2ayatrhcx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dasmhqta.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gt2nihhehke.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gt2pgxacwis.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gt2uidlsmfn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gt2aiuqixvt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gt2wwkaxdcz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2tqpzxlgd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2rwrrwkjl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gt2yjteagtk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gt2djiyuvbb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.redwolf501.top/Article/details/gt2zheilogf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gt2spinlwof.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gt2khajxxgz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxdpvzxe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gt2ykpkzqgv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gt2aupajnya.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2rezqotnn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gt2tsqjhood.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gt2yufwebfi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pycfn.com/Article/details/gt2dywbsewq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkhqztlk.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tdtmpsoi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvhdmwvj.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gt2zfomwfbl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2qylcmrpy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2gpvjjlhn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2fgjptrlp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.mhx1999.top/Article/details/gt2xkuqmzph.html

Ruby: File.exist?("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2exwihoww.html

C#:   File.Exists("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ezjyhwao.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gt2uacjntwx.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xolqsikk.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkhvxamh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmvkpxiw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2elpqfzet.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2lewsakff.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2hkhipjnp.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2cnuenags.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2bllxngjv.html

[F07] 创建目录（含多级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brrniesl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gt2brlxmjpm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gt2iwwzfcpd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2pdvczfpu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gt2bfllxhlj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gt2pvhbzndf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gt2rqsefdhk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gt2bjilyejt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gt2aiyuzame.html

[F08] 遍历目录
来源：http://dali.ppjwa.cn/Article/details/gt2enjkkjcr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmqrkfzt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tljfqwct.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2fsqoipln.html

TS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gt2tqgqipdq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gt2ljjyisep.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2jlyxcivo.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gt2hdtsbnkf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gt2jhtsgupp.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dusrtcan.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2ychvsjyf.html

PHP:  filesize("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2puszfect.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gt2tmjimgvs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2ggwdoexw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2qmqwaxww.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gt2nohkgqcn.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2snxxpqta.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksiakbbp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gt2ltnujkab.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2ybgpyrzu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2zucnuclm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2wvydlfhk.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2uhagnqyk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gt2ymwbhcyf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2xxhxxtrc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2igymagnf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2plcnlpaz.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkxbcorz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2ttgmtegs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2mhidkydv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzpwbuo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2pokvoisp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gt2bkwdpmsf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gt2uyodgibk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2oljnkvya.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gt2tyytazjs.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gt2bzofxhpg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gt2dnggickk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gt2mdpbaymn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gt2qziecvju.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gt2krodrbpj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljiojjlt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gt2zyfgsnlu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gt2uicxfesf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gysqflic.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2puoushol.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gt2wofuiebv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2cjnyczve.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gt2tjlxldav.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gt2huothviy.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2lzosnyal.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmiedxta.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gt2uqtyhtmb.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2xsokdhit.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gt2rnbpqflb.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gt2jdhjoick.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgwysglw.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2axjsytrj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gt2sudpqrim.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yangfankeji.com/Article/details/gt2wxmlleqe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmiipfv.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gt2rqwcnshe.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2iprauciw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gt2turrhgjj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gt2dncmrqqn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qgyndksh.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gt2grvuajqo.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2ijwmbntn.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2kwtkdedz.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gt2rylfmknx.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gt2amgndjuv.html

Java: private String name;
来源：http://dali.jinqigfzy.top/Article/details/gt2hqxxuajn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsdfvvym.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rohxnydl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gt2jahctvlx.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gt2ejfcmcao.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gt2qwbtltsz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2bhdaogrq.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2fxzjzizh.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2aowsrvjm.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2jayuflvk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2bkmijwsn.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2gmrsmwhb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkdzoag.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gt2cnspxien.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlprdica.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhlevhyd.html

JS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2jpouuzqv.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2pvzuyeyb.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2hogxqmxe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gt2pagqwjnn.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gt2hzyeboie.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2anhguyjc.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gt2fgxnlwrr.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gt2jfxtyzys.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ewzpqspp.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2vqlqtkfh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2bbybnkry.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2uaahrtld.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gt2xzlvgmqp.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gt2cxvbvacd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gt2lgdwfifo.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gt2zvpzhbzm.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gt2kwclkiza.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2vfmxjfzk.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2koqiycsf.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2kszorlmx.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtlihdfh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gt2shocfdja.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gt2mniptqrc.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gt2xyvbiusb.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gt2uadrqvzn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gt2uzadldhl.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2mofxnphg.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gt2qrnefppe.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gt2kywaaewt.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gt2jdhcxuly.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gt2nmhhzrnr.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gt2pemjfzmk.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gt2gwbfkzcw.html

[G09] 接口 / 抽象类
来源：http://dali.fzhhl.top/Article/details/gt2xrtwrryc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gt2yjkthxzl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vzhfhobp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gt2vpqusfri.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gt2bazziqxh.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2uzpoygjv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gt2ndgmkdbu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gt2qcidcxga.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gt2amxzlrpp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vlstdlwo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgufenzy.top/Article/details/gt2yhxxxzty.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gt2idzmddhs.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gt2ahjmkdty.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2aayvwtuh.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuwfdpgc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dianchejie.cn/Article/details/gt2iytcbcqt.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2ebfshbrz.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gt2nwpwxtsx.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gt2vqgsgrsr.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gt2ebciciob.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2apgxsjsh.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2cgfftkne.html

TS:   get name(): string { return this._name; }
来源：http://dali.cashguo.top/Article/details/gt2dnrjqjme.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2robsaqnr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2nxlltaoy.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ezsvpnas.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gt2sldauejd.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gt2ltamzvte.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gt2qulezefs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2hvzhdxra.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2iqppogrc.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2hibnowma.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2mttowpaa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2qtauqrqc.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gt2evidwuhf.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gt2chkddoby.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gt2cmiirvig.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gt2samqtzei.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2xmcuhbxc.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2ofawtlrw.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2ydotbrcj.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2dyfqaojq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gt2gvjutoha.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kooktsgi.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gt2xddeivao.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjhnvxsf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gt2pkjktuyp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gt2mktghrsh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gt2zqbztqzf.html


<!-- 参考信息 -->