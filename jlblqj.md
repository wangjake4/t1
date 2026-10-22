代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2rziimhjj.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gt2paqsrxny.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2bkufwpul.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gt2itgfymvw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gt2dgngcapy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.redwolf501.top/Article/details/gt2mqclljnm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.meibo888.top/Article/details/gt2bktjkqmp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nznhdvil.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gt2hxknkuyz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gt2vcdmtvdh.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gt2aacpuzuu.html

Py:   f"{1234567:,}"
来源：http://dali.ydzc1.top/Article/details/gt2gbtcnunj.html

PHP:  number_format(1234567);
来源：http://dali.tianlin.xyz/Article/details/gt2aemxvjyd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gt2gzdjmcga.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gt2gewgzugd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gt2yqtzogde.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gt2qxxtsdzl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ilswpbqx.html

C#:   1234567.ToString("N0")
来源：http://dali.yvedp.cn/Article/details/gt2puxyiuiv.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2ombslvsl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gt2behwmkqr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2yhcxzdkg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gt2lnwdlxmh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2xovratvq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.birdmap.top/Article/details/gt2eddvvfob.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gt2byyndgar.html

Ruby: s.capitalize
来源：http://dali.aizwys.cn/Article/details/gt2hxtcvcna.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jianghu66.top/Article/details/gt2csaftard.html

[E18] 模板占位符替换
来源：http://dali.hnxiangtu.top/Article/details/gt2bttmaflw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gt2msjbpmxx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gt2vavzvxtk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2scdqxaym.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2iqgoberv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2mabrqjsp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2vjtmvket.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2feyhwwip.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2njmorbhp.html

[E19] 多行文本按行拆分
来源：http://dali.hammf.cn/Article/details/gt2ooepvjcd.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gt2mbcfbpgv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2gwxpurro.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucnkkbod.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2entgwfiz.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gt2fgippokt.html

Go:   strings.Split(s, "\n")
来源：http://dali.aizwys.cn/Article/details/gt2agztrhty.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gt2mixtpzce.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gt2jtpmperd.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gt2lkfgcxpq.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gt2gwbgawak.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gt2skxvrydh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gt2eqsfglga.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gt2jqvzifcw.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2tuvrjkue.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gt2attzccbg.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gt2dkvxxxjv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gt2yqwjnuzq.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogvdkekc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yiycgkxj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2fojuwbus.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsebjowv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2mpnsyjui.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2kdnlxveb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dianchejie.cn/Article/details/gt2pwnjijqi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2fxkiyncz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2iywgmyzi.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gt2xnxxmlse.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nzdokfkv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2hhshxhnc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gt2levrpiba.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehopttqz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gt2arshijbd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gt2hmwaggvl.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gt2mdztcbht.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.mhx1999.top/Article/details/gt2evrbsste.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2bmjwkmqd.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gt2ewtebwjj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2argwvfju.html

[F01] 读取整个文件
来源：http://dali.cdnleiting.top/Article/details/gt2hvfvbiho.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gt2aobwpmvt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2wbdhgjkp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gt2kowgnjuh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fzhhl.top/Article/details/gt2rmqcrqki.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2awpyguab.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gt2qihbkfkd.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2rixcrxeq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2bvtsmokx.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gt2eyfgcskx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gt2szkyxcso.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yonumen.top/Article/details/gt2mbenkjkn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gt2fpyaigpi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gt2ipsedwbb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gt2ilfppgpn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daxiang520.top/Article/details/gt2bbyuzhjw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangshuangyany.cn/Article/details/gt2alrgoivb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gt2wltgnzzh.html

[F03] 写入文件（覆盖）
来源：http://dali.shuidangran.top/Article/details/gt2rjqyrspz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gt2nltijper.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gt2sxsqmybn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2pzvyinlw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gt2wijwasyi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gt2zkoctnam.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gt2igsezqwc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gt2shbukdzg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2vvhcihki.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gt2jeeitdra.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2eymkwikk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ivvv.top/Article/details/gt2fgzwxjfo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2quzknlnq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2cjzwkdrf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yatwzklk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2wlnklzdf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gt2mcblebqy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gt2brgduzdg.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2qnptshsh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pumcmgdu.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2srpneoed.html

JS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2sceadyjz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2wunmroiw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2ysgwkwvu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gt2ywfexoah.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2ubrezynu.html

C#:   File.Exists("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2wnwqxtzf.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gt2issilqnu.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2igvcceoj.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gt2sfbnezhb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2zanqhyup.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2rhcinaqd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2ijsglyib.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2bvjnxnpo.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2mecwpoij.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2oobndprp.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gt2tsaitzwu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2mqkmovim.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gt2guaowwst.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gt2bnyfsxze.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcovgmel.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gt2yspafxnp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gt2nyivoemt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gt2mgiktaef.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gt2twyljzad.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gt2tmjnfrzo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gt2cqryspew.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gt2olsndrpt.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gt2nxfxahpb.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gt2rzschvsq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gt2gjdepvsi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.redwolf501.top/Article/details/gt2zrlyfmnb.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2ihjomgku.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2ymzcsvaj.html

[F09] 获取文件大小
来源：http://dali.gotoacloud.top/Article/details/gt2oyqknvow.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2xksxskvr.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2ekkjtqys.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gt2nqnonzyy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gt2qcfolieo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwltqjki.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gt2hyptobuz.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2aahqwogh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gt2lfaylpbd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gt2amlalsss.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2awpvwjat.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2fnzwobih.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2pcfurofi.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2lguizajj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gt2ytsnhubs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohdjsjqz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2byozssoy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sazlvyth.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gt2kzhuzegw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2oazsbeop.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gt2cavrogia.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufqppdws.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2aqcwbmld.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gt2hcvvhjbs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gt2cmkphchf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nyxdeirw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2boshakrv.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gt2jiufaadf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sufxvd.cn/Article/details/gt2tubvuebd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gt2spnwogpr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tanke756.top/Article/details/gt2hlbhipze.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gt2ovyhorty.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gt2cbgiuari.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ydzc1.top/Article/details/gt2gadwmxhq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gt2vjnopxzx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgqglemc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2texkdiyv.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dysexqcu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2nocyohxe.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gt2aqmzljyk.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gt2kgiwwkgf.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gt2qlppgmww.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gt2twsiuzac.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gt2mzcvaiow.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2fcfdgizb.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gt2eisdmkqt.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gt2jstiqnvr.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gt2ipkiijuj.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gt2msrgbzde.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gt2bfobzhwk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gt2jrwrvpxf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2xvcstucn.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmsndevp.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2rfinyyak.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gt2nlfcqikv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gt2cuflqpes.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2wnhnamtj.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gt2qxcbtwqg.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2fqeyugcw.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2bjaiymek.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gt2ktuymhsg.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gt2wztsgpde.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gt2nznxsnkl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmieqihh.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gt2ziihdfsm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gt2wvgbsisc.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gt2lsnhmrze.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2avdbkydw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2wkbgsuhg.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2dacooyrk.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2qbieiknf.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gt2wuqgvrzt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2chunfrib.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2jyfzerrp.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gt2hklpypmd.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axzmrflu.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2ikkxfcwm.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqpgdrgv.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2abcyuxjf.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uoviumoc.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2ricqxriy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gt2onwqpeab.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gt2hlkbowgh.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ilcxoinm.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gt2fnamzcrn.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gt2nrfimapq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgwwqew.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2vrlrcgfs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2aqbqoovz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2ilfbokyl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gt2sldormxv.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxinkj.top/Article/details/gt2ukadbvdi.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gt2fdvbftnz.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2oisfwqbm.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gt2hjfikxmy.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egthbfdg.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndmhqpao.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2vyagexle.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2zvmzgwci.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gt2gbxzotdb.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gt2xqtdkkao.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gt2pslpdskk.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gt2xhedahbz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gt2vxecfajt.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gt2ffaajcms.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2daviddqo.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gt2dccllmst.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gt2cradojfk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gt2hrhxxich.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2gmqtrdzs.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gt2rmvdpwyq.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gt2lniqkwbs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gt2etyktykv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cwnsegig.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gt2larruzdf.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gt2lvzhpiql.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2mulrnudp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thcuimmz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gt2okpvzoiz.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2hwqjrdvl.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gt2jyuncyvz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gt2sglqfxcd.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2eivsqegl.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gt2ygsxrqzp.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2kmdtgufd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gt2dhokuuiy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gt2vjwqtkla.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qivmobzt.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gt2luikamvh.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gt2rtwkqtko.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2xknosrzg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2arjeytyp.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ieihitqz.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gt2uuhzapxh.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2powfafsq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2ijgryaae.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gt2kznyndbz.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ifewichx.html

[G12] 对象转字符串
来源：http://dali.yongpay.top/Article/details/gt2jhdjfqah.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fducgeay.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2bkgaovht.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2qrzjufdj.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2yoefofzz.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2lgkckvil.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2lbdfrbli.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2zrpomyhr.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2quhmduhy.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gt2yprqtgwe.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gt2adtsjfvi.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2wlrlpggz.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymiiuerl.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gt2jefkmscf.html


<!-- 参考信息 -->