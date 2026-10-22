代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gt2ojccnadq.html

[E15] HTML 转义 / 反转义
来源：http://dali.cdnleiting.top/Article/details/gt2ymcoarwc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gt2lmvbqdnn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gt2qoejoagv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xkllyxkr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gt2fpqsosjx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gt2evxhndjo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wsbtijpy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.redwolf501.top/Article/details/gt2seosvmql.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gt2qefanjpx.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gt2fjxdmvri.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gt2puoaasqj.html

PHP:  number_format(1234567);
来源：http://dali.hysaishi.cn/Article/details/gt2xajdbryi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2vhjupflj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gt2xyjchipb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gt2vgjtnxfh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kfldrinv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gt2wsnjwhoo.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gt2ijzezvsw.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gt2umdivowt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gt2gbvhtyqk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shzxlz.cn/Article/details/gt2tgrxezcb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gt2awmkbsdv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gt2yplrwweu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnkycbxq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gt2wupcyiyn.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gt2ytzrgelv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxinkj.top/Article/details/gt2aaslblnw.html

[E18] 模板占位符替换
来源：http://dali.zhongyouzk.top/Article/details/gt2tjjhcart.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gt2bivtwjfk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gt2awlvhmla.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmgoyrnc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2eaicczvz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sweek.top/Article/details/gt2hvppallq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2qkxvlhvf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2szrvlkay.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ppjwa.cn/Article/details/gt2euauayan.html

[E19] 多行文本按行拆分
来源：http://dali.guowangkeji.top/Article/details/gt2rmnbadem.html

Py:   s.splitlines()
来源：http://dali.ivvv.top/Article/details/gt2rvunmict.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2jguvejlg.html

JS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gt2hhkqkucg.html

TS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gt2wemyfhqa.html

Java: s.lines().toList()
来源：http://dali.c1oappe.top/Article/details/gt2ibzjrwab.html

Go:   strings.Split(s, "\n")
来源：http://dali.dashuyun.cn/Article/details/gt2fudqufgt.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gt2avasgxtg.html

C#:   s.Split('\n')
来源：http://dali.smart0.xyz/Article/details/gt2qxphhwvb.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gt2debyycvi.html

Py:   if not s:
来源：http://dali.316326.xyz/Article/details/gt2ompcopsz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gt2mgktvaxc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gt2mgqbjobe.html

TS:   if (s === "") {}
来源：http://dali.yueranfly.top/Article/details/gt2zbocgftj.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2jtgjdfwf.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gt2ceklayhs.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gt2gnrqebtb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wiqfqyqt.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gt2iiyegdmo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gt2gfnlxigx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2dojnqnjq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2ijvgyblf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2xqcxxoog.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2gxtqgcau.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gt2orsoxhhq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2cqieujdg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2tmfvsyun.html

[E22] 字节长度与字符长度
来源：http://dali.zdqjudy.top/Article/details/gt2imjscguw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gt2rdoxgxen.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2ykpkzdoh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gt2lgwdsdhv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gt2vtrsflnm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gt2tjvpvvmg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gt2kxwhuiht.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gt2cjbrvngx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gt2jbtyfeir.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2gpbkxija.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gt2fmjdnbft.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2gtztsahx.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljuduwvr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gt2zkhnmxhc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2kvrynmxb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gt2istknqqf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2nqfnahzc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2xxelpnbn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gt2hwxqvmda.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2eeewrczx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2nfewyxhs.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gt2dvohdmgv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gt2mwvihhti.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gt2gygqxddb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gt2gtoujghf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gt2eqxfernt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gt2ssidmsms.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.kuanghao11.cn/Article/details/gt2iruwjymp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gt2dgtmucpi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gt2pciiikjm.html

[F03] 写入文件（覆盖）
来源：http://dali.hammf.cn/Article/details/gt2hjskuswu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigufen.top/Article/details/gt2qebawnpq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwtqxarh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2wzrrzzan.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gt2izoroozl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gt2yhlprasq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yueranfly.top/Article/details/gt2cjbmjvau.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gt2qgqpxlrs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gt2gkyrwyeo.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ljyzljit.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gt2qcrxftrs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gt2ijcbaogw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzikyjxt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2qbfurtto.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gt2icrtffor.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2azoefues.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gt2yltnjaqc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aizwys.cn/Article/details/gt2byvujshv.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gt2dtkvizec.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjyeoqxy.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2scmtmkdd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ubkeqbak.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2xauhtcmh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gt2rrrncfrd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gt2lfnrleto.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2cmgclpqv.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nesadgfp.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gt2grbxlqka.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2mvucrwlj.html

PHP:  unlink("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2fwnjhrwq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2oggugqoc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2jzwyxhtc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozyaumdn.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnmtaidh.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2kluqndzt.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2btxpomdk.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2vomdxmko.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxgcszxi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gt2ggfcgjyl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gt2ixndqiew.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gt2tzbzxbkv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gt2mxrglwjc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xinyue.icu/Article/details/gt2nilsljve.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gt2vlyceidc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gt2rmneoxue.html

[F08] 遍历目录
来源：http://dali.shzxlz.cn/Article/details/gt2rjwcakgc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gt2anzbcuhe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gt2exrinabb.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2jgjbvmsg.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2nitlxzsi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gt2kcrgymcq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zycfv.cn/Article/details/gt2plqfarnt.html

Ruby: Dir.children("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2igjbomzb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nazkcvnf.html

[F09] 获取文件大小
来源：http://dali.jianghu66.top/Article/details/gt2kkplbhle.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2mutsskib.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsezdlvo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvcvuwfn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2xzyreekd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2qvsvifqi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gt2ojboiqva.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpjgabde.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258.top/Article/details/gt2uonhbkhf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptfhegxc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrurdlfd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2hvqqjaes.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2epyakodl.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2fhxampmh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gt2tmxaxemp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2jjjbkqwv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgmwwpgk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2tznivefe.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gt2bfknpyvh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2johvibub.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gt2flvpejak.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2bylkpccp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2bhrqmwrs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xinyue.icu/Article/details/gt2qshkqycf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nwbrower.top/Article/details/gt2mmlmxtap.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2myxtaoil.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gt2roilnfxl.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gt2uegsrhdw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gt2rkypkfde.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zdqjudy.top/Article/details/gt2wdyvauvd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cheryme.top/Article/details/gt2lhrihuky.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gt2wdmvbyyo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gt2thwatibl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gt2ucovbwxz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gt2romhaaqs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2qeucmslf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2dytdeyfm.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gt2tsccxlde.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2rucmjbrd.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gt2ugeoaawg.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gt2xnwmetbr.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gt2jablvfhe.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2vegyqbsh.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gt2raaoumxc.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gt2hdlcqqhm.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gt2piagygjf.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gt2uampuums.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2mqoeqefk.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gt2bbrqbwkv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gt2wlfffxdf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gt2eoalieji.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulmqfswt.html

TS:   constructor(public name: string) {}
来源：http://dali.c1oappe.top/Article/details/gt2ramzfauk.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2ixzccgkc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtdwixxv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2yjdtoqss.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2stihjxvb.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gt2vfamhgum.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gt2fqkwdkwv.html

PHP:  public string $name = "x";
来源：http://dali.yueranfly.top/Article/details/gt2jrriywle.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gt2nxkehitt.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2jsswmunl.html

Java: private String name;
来源：http://dali.yanxiufei.cn/Article/details/gt2ciorpzew.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gt2xofloiny.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpownzjc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gt2idzvqwdg.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gt2wapmtsnl.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2ylheuizs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ragrhmxn.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2iwivhlhr.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2zryduevo.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pvqagouk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2ybfzdlse.html

Ruby: def greet; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gt2umeljkrz.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gt2iemczjyk.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gt2oguftfhb.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gt2vbuivtfv.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2andpsnig.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2bztyxrkv.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2brdduyll.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2mhqmvunv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tanke756.top/Article/details/gt2faevddsm.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gt2rpaneikm.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gt2haiwcypg.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gt2zvuuwsea.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gt2zmauqtea.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2xyyebhiw.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2imlyrogp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2vxrzjdcz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2kmlkgkgz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gt2louphpkf.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gt2rxamhhpy.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gt2rvstzdsb.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gt2lopnzkwl.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sknotlhp.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gt2znllpypj.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2hrqsvtcv.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2vmzgtbvs.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2fyugwgfy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2logwnhhx.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gt2rdcpecmm.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gt2cbynmdob.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gt2uvkwhgwl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gt2skbitpgn.html

PHP:  public static function f() {}
来源：http://dali.jianghu66.top/Article/details/gt2jhglxvat.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2prkjgxop.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gt2krxildfw.html

Java: static void f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2jxedmsel.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gt2pvshvujr.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gt2umqwgxkk.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gt2rrnyndof.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gt2hzysxbks.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuanzhike.top/Article/details/gt2gulrdgpp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gt2fcwypphb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhqzoqny.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gt2vdksqeyg.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gt2xekksmod.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gt2rfjdnwvv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gt2dwnjgbkd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mghrdwyv.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gt2zvatzwov.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gt2ahvxdibb.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfvvjiht.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gt2pxinyxxi.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2ithakkvg.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gt2plkucyvm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yanxiufei.cn/Article/details/gt2kfhksnmo.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2fhzafgfl.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gt2ofmiizyx.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gt2vujenwrb.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gt2rigjmmna.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2icaommte.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkkzacwh.html

TS:   get name(): string { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chklkjgy.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2pnugukjf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2tkusdwqi.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gt2itivxptk.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gt2kmfyuwgk.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2vtzmjjde.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gt2hdxqcjwq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2uhxuaeba.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2qwlxcsqi.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2tkmsbdhf.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2muzbqpdv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2sivtuvff.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gt2mwgvgtir.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gt2yymnybko.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gt2kdywpcog.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gt2kbljoeja.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2ucjvrevr.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2fxsacimc.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2jcyetvvz.html


<!-- 参考信息 -->