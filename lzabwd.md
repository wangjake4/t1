代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtqxzdavsz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gtirrgmavj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yvedp.cn/Article/details/gtirfcxoxv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gtijzwwpdw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gtfydzvkqj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtgidqssvd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gtitdwnbci.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gtpqjxjmos.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtnnxsnluj.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gtxpvthbkt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gtvwgbdkpp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tanke756.top/Article/details/gtndnoevxd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtkamusrig.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gtswokhxin.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yangfankeji.com/Article/details/gtxxqbgevs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gtynoidchp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.0kj1m.cn/Article/details/gtmjknsdoe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258888.top/Article/details/gtsltrwrij.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gtjnkfaufm.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gttrkmzvnf.html

PHP:  number_format(1234567);
来源：http://dali.tianlin.xyz/Article/details/gtydnsswdu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtzytpnmwu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtbcpetcsj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gttrztspqv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gtkwmmltaa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtoamhvqkd.html

C#:   1234567.ToString("N0")
来源：http://dali.smart0.xyz/Article/details/gternsnret.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gtsywzhzvo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.snrcjt.cn/Article/details/gtuutazfzd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gtwprcitjg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtdncqtgef.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtnqmmzcch.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtvoapikie.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gtbjgqkwjw.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtcmmoilzx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gthycirvbf.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gtbcitztxc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.bjfxy.top/Article/details/gtijgvziud.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gtsjsgeiwr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtqydshjez.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtokdzuccw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtviekgovw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gtrnzjswwc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gtfrdbbvqo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtldaxfrrs.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gtcwcfisbg.html

Py:   s.splitlines()
来源：http://dali.yongpay.top/Article/details/gtgecifcyt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gtxpukjozx.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtildjepdy.html

TS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtqsomklim.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gtjrzahimz.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gtbsgqpfsl.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gtsxhwhils.html

C#:   s.Split('\n')
来源：http://dali.gaohongyu789.top/Article/details/gtghxoernb.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gtlafdvvjq.html

Py:   if not s:
来源：http://dali.gzhubu.top/Article/details/gtuasendon.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yanxiufei.cn/Article/details/gtoyzwfmyh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gzhubu.top/Article/details/gtayuiypfp.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gtafcfdhov.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtzcnuvpmc.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gtwwtovzam.html

Ruby: if s.empty?
来源：http://dali.chenlongwang.top/Article/details/gthdzojowf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtrkrgxtof.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gttlvyozbe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj202588.top/Article/details/gtgzvnlnxr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtouhxtsfx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtpqoiwiim.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtldxjpiav.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtgswhlpcz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gtvkmywfuh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtthontwgt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtkjddwasm.html

[E22] 字节长度与字符长度
来源：http://dali.hnxiangtu.top/Article/details/gtjgtiglsn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gtrgnogupp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtyoprqwpe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtobkqrgsr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtpdufukhe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gtsmnwhzft.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daria6918.cn/Article/details/gtdkmewyhp.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtjpmmbnbs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtzzxilogf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtvvdxsxvd.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gtxsgrihnb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmvsevknc.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gtdmbjaqqk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gtwupwepio.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtmcqasody.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xinyue.icu/Article/details/gtnhrtlwnd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtreoteopx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtfjgkkwww.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gtgsphraus.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gturdtzapd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtcmiyupwi.html

[F02] 逐行读取文件
来源：http://dali.yvedp.cn/Article/details/gtdmejtvvh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cqqwz.cn/Article/details/gthpmcbkzf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gtublszlcr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtizyqruoz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gtszytumpb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtengnfzrm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtfnpldvpd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtavxkmtqu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gteltbyyfr.html

[F03] 写入文件（覆盖）
来源：http://dali.wangshuangyany.cn/Article/details/gtjlujomtw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gaohongyu789.top/Article/details/gtyrpctott.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtlprrvcbk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtdaifynkn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtnxprjtrz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gthshagxml.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gtixptqpbq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gtvscglaeg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtorspiwdi.html

[F04] 追加写入文件
来源：http://dali.gaohongyu789.top/Article/details/gtjbetybwc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gthkuupybf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gtusbiujpz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtjoqndowh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtmyxrpmgw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dashuyun.cn/Article/details/gtudqcscwv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzlpxnes.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gtxtpylziy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gtibogbbkc.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gteianzdcg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gtgzatjhff.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gtqpyviljr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtmcjkwfvb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtghftwpdn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtltqonjwa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gtceyuycfc.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtwvjarjqr.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gthsbcaytn.html

[F06] 删除文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywtlbrvw.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtfrnqpsmk.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtgzbezqod.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqpktjfux.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtqlpjdxjg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtjmboubrg.html

Go:   os.Remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtljfjnmjv.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtawijwkui.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtppqmyyks.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gtvmfjetlv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtqtvwdcpm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gtuonasiek.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtxyioyocb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtvmltvcpp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.redwolf501.top/Article/details/gtqsspvxka.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gtycuojexz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gtvbuxkmqs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gtzvgqxvdc.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gtwshwevns.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtpyqysqsd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangshuangyany.cn/Article/details/gtewlftfsc.html

JS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtrxjrvzzk.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtbxqpvmyb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtitzeophm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtulpwjaod.html

Ruby: Dir.children("dir")
来源：http://dali.sxryk.cn/Article/details/gtcgevbldc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.redwolf501.top/Article/details/gtkknqfbni.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtarrpjypx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtaaoousns.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtjaegknnz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtkarcklco.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtaryypdfr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtxygohjej.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gtreunwhgj.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtdmxfdhug.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gtptctynnp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtijdmzavs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtsgfkgnnl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtxgiuaeld.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtkrzhyczg.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gthpetaguz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gtckezugkc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtimgealjv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtnjfbmzng.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtcwvfsxoi.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gtopkxwekj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxpybtew.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gthcwrmrim.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtxvbwazpn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtpihuyvry.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtithasmpj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gtfwouwdif.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtorvjeayy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gtfiwenhxd.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gtuxhwxcjb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gtoiagajmb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gtufibqhjb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gtgteplkbk.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcmtnnhp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gthsuomwnf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gttbpyqlyg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gttupqhhws.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gtefbbtrzl.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgxgtgkmb.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gteonrbpyl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtggzwhzwr.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gtzxqqavym.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gtdrlacdos.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gthxyvsdtb.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtaldkcuhb.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gtirgjkfiw.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gtimwytvsc.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gtkcwlbrda.html

Ruby: class User; end
来源：http://dali.mhx1999.top/Article/details/gtueeqbrga.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtjiadqrci.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gtgpqapzhv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gtxmarkelf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hammf.cn/Article/details/gteopxklmu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtmutfffmb.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gtwchvjjng.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtgmbwqemi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gtaaawzytp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nwbrower.top/Article/details/gtrlxocoel.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtclnvekdl.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtjwgjylud.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtaxkfidgz.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gttyxdpohs.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtvojxyzmm.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gtvwzialob.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gtkduoxirt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gtjhhehfnz.html

Ruby: @name = "x"
来源：http://dali.jyoumei.cn/Article/details/gtoxctirpd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gtgzammtdq.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gtkacbukip.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtnwnheszp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gttjmecguz.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtrnoelicq.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtfoangyac.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gthjwwojfb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gteteftxko.html

Ruby: def greet; @name; end
来源：http://dali.316326.xyz/Article/details/gtnnjjuizt.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gtbcmugngo.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gtqvihokkf.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gtynossdal.html

PHP:  class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtfklbdogs.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gticjkhsir.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtyvgxfelu.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gthiehvdar.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gtydkrppej.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gtbjrazgze.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gtmwofmgtu.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtoywsbrqq.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gtpdtjpusb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtcjqkgvje.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtrasuowzm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtstjaaksm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gthckcgjgf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gtlmeqokgh.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gtderlmgat.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtkbxsueep.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gtzebrzoqa.html

Py:   super().greet()
来源：http://dali.havefunace.top/Article/details/gtdfsegwso.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gtzxkrosjh.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtzofkftex.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtdglsdjdg.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtrylnrpph.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gtaxilqutw.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gtgutotzjl.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtxexsyktb.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gtktklhhvn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwlljnnz.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gtwquheqoo.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmzxrtwdr.html

TS:   static f(): void {}
来源：http://dali.yuxming.cn/Article/details/gtzbnukbcz.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnnlmrjh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gtngpsoisf.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gtglhmdqsv.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gteobdarxm.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gtjehzrtpf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aizwys.cn/Article/details/gtbjsoiine.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gtsrfnadoj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gtevpvkvpc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gtxyqdzwpa.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtcpxiosnf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gttvatngqy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gthvgnwgfn.html

C#:   interface IShape { double Area(); }
来源：http://dali.shuidangran.top/Article/details/gtsrnpvxmn.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gtbpoqosba.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gtbvencwbh.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtsioczwod.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtwlkirsxs.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtvqolxznx.html

Java: public / protected / private / 默认包级
来源：http://dali.bjfxy.top/Article/details/gtxsjdmuit.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gtctqkdrej.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtyasmegui.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtozhyrhjq.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasoyznto.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gtuajdclhl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtsypdgbmf.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtbmljqhev.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gthfizzusz.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtbpvcnowc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gthpqmeqhw.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gtughfkbbp.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gtblpuvfni.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtnhoozrrv.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtedgbekbx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtzauvydvx.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtvclpnivf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtvosugmyx.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxagljul.html


<!-- 参考信息 -->