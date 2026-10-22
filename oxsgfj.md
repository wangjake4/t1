代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbftqxum.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gt2rkqispla.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhoulong.xyz/Article/details/gt2wnymxbtg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gt2cpndzmjg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gt2anfvhqlm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yangfankeji.com/Article/details/gt2rsjmpzix.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gt2rgahxvbe.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gt2urpfdypg.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gt2fuejglvs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gt2onmbuqhl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gt2ythwydsd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gt2knvqxmcs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gt2jxdqrspn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2obsqhcal.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gt2ctfqruhi.html

[E17] 首字母大写
来源：http://dali.vqdsnc.cn/Article/details/gt2eebkesxd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gt2gcxkssnj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gt2uoztbile.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2chnlgiuv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gt2gishffrx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gt2mjyqmvmx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2kpgzvnxl.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gt2uekezvxy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhewdlte.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gt2pnxqibml.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hysaishi.cn/Article/details/gt2iuwfmowr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cqqwz.cn/Article/details/gt2rqclrkrh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2rrpounnu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2xoqkntdy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2ftrkgnno.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aovfhbvs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gt2htgbrvng.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gt2eslsebpv.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gt2stdtxwas.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gt2grmpixdk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gt2ugjjohhs.html

JS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gt2bkdgpban.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzbxudqg.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gt2ativnwyy.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gt2rdfjngrg.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gt2khtnvfjj.html

C#:   s.Split('\n')
来源：http://dali.c1oappe.top/Article/details/gt2qicjtjzh.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gt2bbpjjync.html

Py:   if not s:
来源：http://dali.9152youxi.cn/Article/details/gt2zuhvkdvv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gt2jmglgeox.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daxiang520.top/Article/details/gt2qtjryzoz.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gt2rjqfebra.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2gienjfte.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gt2wxczdxop.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gt2lqiapzel.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2yhchpbji.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gt2zngdpxfy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gt2zfpgwsga.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxsoelop.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wbzzskdo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2rvpukaxr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eymdacpn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gt2qxmtzygu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2ktnamevy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2jkevlkmn.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gt2nsqcyxja.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gt2fhkqqwsx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2swzfcrfl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2dpgugvgb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2rlfcffba.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xinyue.icu/Article/details/gt2regwliwt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gt2wmhphzvj.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangdashe.top/Article/details/gt2disfprru.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gt2zlgonplb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2kspvczgg.html

F. 文件与目录
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpcynjse.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2igtrjcgn.html

[F01] 读取整个文件
来源：http://dali.ppjwa.cn/Article/details/gt2udlcjxzi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangdashe.top/Article/details/gt2xfavsuvj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2jpuqxclv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gt2eawxumng.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkkrvoac.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqyzzdzn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gt2aozfhwis.html

Ruby: File.read("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2weajjuuo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbwuqgub.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gt2pdcotkxl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gt2irkvmdsm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gt2dyrbauvh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktymkout.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2johzarpm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gt2ekbrqqwq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cdnleiting.top/Article/details/gt2yurpnffn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sysykeji.top/Article/details/gt2vbxxhbuz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gt2mvyixmeo.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gt2dfizcacs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gt2dypvxopd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2rpgbaylr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2abigiejp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2ydhnewla.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxuanxn.top/Article/details/gt2fxlmztwc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.havefunace.top/Article/details/gt2hrakderq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cheryme.top/Article/details/gt2teaqhhvq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2dmezenrb.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gt2vmvzbyzp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2yzacpxle.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hfpthk.cn/Article/details/gt2etoshagu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gt2hxtlaadv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gt2lktpqaqd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmmdano.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gt2rxycvlqt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gt2dvmeqyfw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gt2fqjeoknk.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2oraqcctc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jlsjyb.cn/Article/details/gt2gkjysdmq.html

PHP:  file_exists("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2lbsfjjdy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkctywx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2dpmxmoni.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2usremghe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gt2wjzdqvbq.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2lrxnaxjf.html

C#:   File.Exists("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzpufmeg.html

[F06] 删除文件
来源：http://dali.redwolf501.top/Article/details/gt2qbqrpehg.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2yseguljf.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2hakpsfnc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2qdlaljid.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2foyvumle.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2sryztlro.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ismtfnbc.html

Ruby: File.delete("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2yiccffui.html

C#:   File.Delete("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2qmroxqmc.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gt2uhpkyhoj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2rbevvjbk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gt2okzwqzzr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2kidjdzoy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2vneyronb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gt2tckiostq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gt2uyiyjemd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gt2wwttnyvd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gt2sgvlehwz.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2urpmxddr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258888.top/Article/details/gt2btksabji.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfnfiwzr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxxkadpe.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmqmwjvf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gt2znknxgvk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gt2wlofhwev.html

Ruby: Dir.children("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2ntoyogew.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgmxbaif.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gt2rjvsvpjd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2uybzhide.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2yccahcye.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2gzpchadc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gt2afuynxpy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2xjmhwrmb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gt2okelddpi.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2aqqyufyd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gt2ejvoungd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gt2yiyggqkc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2uhugvrmr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2amdacezu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2tfumqdii.html

TS:   path.extname("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2reckynod.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gt2ultrbqcn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2skvsddkp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2iyzrebhk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2dcbuulyf.html

[F11] 复制与移动文件
来源：http://dali.cashguo.top/Article/details/gt2biynwcgt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2nitgjpuo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhqznkql.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2yaibnttm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2thtjhxyi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj202588.top/Article/details/gt2zomixilz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhmxsszd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2fjzpsnhu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gt2yygzrrkz.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gt2imobeprv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gt2orzqcibj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xylfe.cn/Article/details/gt2eqqdyciy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gt2xsgvkail.html

TS:   // 同上
来源：http://dali.sxryk.cn/Article/details/gt2slpmnbhp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gt2eypjeunr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gt2xenckjks.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gt2rkurednr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gt2shwdcmzx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzafqiec.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gt2uzaayhbk.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2zscstxox.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gt2knuzkwtc.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gt2awyzaypn.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2nsvcljyz.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2xbduxrvq.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gt2qsxczfty.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gt2mszmmwie.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gt2zbtmfueg.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gt2lkmsbeav.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2lciadbzg.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gt2mlxalkiw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gt2hbhubiqz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2kafusepz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2hfqaqvcu.html

TS:   constructor(public name: string) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbhnnmbu.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hyfufyfy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2alwwvjgd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gt2yqfhdkbv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvvamzyd.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2lncamgga.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2xdzxwcaw.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2jbjefnhe.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2igxrazti.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gt2ytbuqygi.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gt2oxzjavkl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkritqix.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2kygslocm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2cyawnmef.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gt2ldwjpxrw.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2zaiiowhu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2sozvffhe.html

JS:   greet() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2auenzxdj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2sdcjmahd.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgwgskst.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2svxnokcg.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2wckfrjrw.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2ihyzmhtt.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gt2kzrdxqwj.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gt2gmabxjim.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2dzfhmrsn.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2vdhjmzxf.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2omklpdtt.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2iveympeq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erhefeud.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dlmamtmm.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2gxjpccru.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gt2agyvdhyr.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gt2dajlokjh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2xvicjefm.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2cdnsijel.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2aqmvwowo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2evrzncty.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gt2wzyxowun.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2spewqixt.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gt2hdnfcmri.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gt2ngcpigyy.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gt2jieznoob.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gt2krikqdzt.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2pmjhhlqj.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrpxwzim.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2mhfunblr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfeiohoa.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gt2lyhvoird.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gt2acpkjmjx.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gt2xnyesodk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gejaomgi.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqeuekdi.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gt2xnbgpfus.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gt2heqgdmbw.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2uynopejm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gt2zemcgfwr.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gt2svoejulm.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gt2sefowyky.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gt2coipipak.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gt2njfkpgqs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnohgzud.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gt2xvlxyrve.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gt2fipxnrnk.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2ryhphvtw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.havefunace.top/Article/details/gt2chqemafj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gt2spsbziil.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gt2vgrdquad.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gt2anudpvfq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gt2tvlkncyd.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2jlulzpax.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nndmrllp.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2unfiiqfo.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gt2thhvfolu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gt2xoymxjfg.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2jamurybs.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhydrktw.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gt2onqjffld.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gt2jduefjhk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2toxmgyql.html

JS:   get name() { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gt2katmzapp.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2mufmwkht.html

Java: public String getName() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2zthkksed.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2uifwsjek.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gt2uaxyhvku.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gt2ktmgddyz.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gt2vrnbbmvy.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gt2ymppqdeh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2mfhutiva.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2keqnurzm.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ebpwpoty.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2wxoiwesd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2gjpsehzp.html

Ruby: def to_s; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2luygjivk.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gt2ptlsippu.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gt2notdprnr.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gt2ideqlftf.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2ckfrcoyr.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2jhayccan.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2okdlydhw.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2dmjwipla.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ppjwa.cn/Article/details/gt2mwdjwbtd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxktflx.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gt2pklltmso.html


<!-- 参考信息 -->