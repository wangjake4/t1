代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2ipcefnnb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gt2sktxtprt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj202588.top/Article/details/gt2pqtqagpw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2namwotja.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigufen.top/Article/details/gt2zpilzupe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gt2hoscpawk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gt2jhibwlal.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gt2tcbstpak.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tian-w.cn/Article/details/gt2lyjmxctb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2ninmjpyn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxtqgydd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.kuanghao11.cn/Article/details/gt2gshwbchp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqnhtomi.html

[E15] HTML 转义 / 反转义
来源：http://dali.svipenyu.cn/Article/details/gt2ppjjwijm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gt2qnfmyxsc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gt2cqrscelp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gt2hocaihvv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2fbgecxux.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rodbrhry.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gt2vutkjqym.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zuccdomi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2hjififuz.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gt2gyenhvyj.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gt2yrsfwvup.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfgxzghz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gt2unycoyke.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gt2bsjzphol.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gt2rqskvdql.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gt2bqtqughe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gt2qfrzcydp.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gt2rgwljydd.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gt2enonooet.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qacbfiev.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gt2vkmubmtc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2itdnjiqq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gt2veibgqit.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnnxnols.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gt2rcsgvheb.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gt2msgqnmxq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gt2zfqidqiw.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gt2stlqqmcj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gt2jtjmlulv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hammf.cn/Article/details/gt2oudxkojr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2omoddhwe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2uvzdbtyy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2vbltzkzn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysioxikf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2vebitwnv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gt2opjciorp.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gt2uxsurqaw.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gt2zyskdnau.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fnrxjtgj.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2pdukqjdb.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gt2cthftrwc.html

Java: s.lines().toList()
来源：http://dali.jianghu66.top/Article/details/gt2qxkofbse.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzyywtyv.html

Ruby: s.lines
来源：http://dali.nanxinkj.top/Article/details/gt2lbofyinb.html

C#:   s.Split('\n')
来源：http://dali.yvedp.cn/Article/details/gt2phvjjbno.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gt2esxyasfq.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gt2qmcooyqc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxinkj.top/Article/details/gt2fbcnlmaq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gt2tjisdqmz.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gt2izrmvaru.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gt2vnbncjyi.html

Go:   if s == "" {}
来源：http://dali.hysaishi.cn/Article/details/gt2fdflbehn.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gt2trwtuwxh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258.top/Article/details/gt2nvnduptb.html

[E21] 超长截断加省略号
来源：http://dali.jlsjyb.cn/Article/details/gt2tdzakdaw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yvedp.cn/Article/details/gt2mlldybjc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2xfnpfblu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2attyzvtc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2xyvuikzh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhmbupms.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tianlin.xyz/Article/details/gt2glbcqvmw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2bqcmqyku.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2oozpgsti.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gt2mbbjpjtj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gt2ftpozjzp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whdglhuc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2bxuanmph.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2rmgldrhk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2hnjbehwu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gt2vyllnlyp.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2yaxzfxvs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gt2haywhrty.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmdpcslk.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gt2pjvxionj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2oacnszzm.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gt2ckfjgiqb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gt2wdktyyfk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2rojvualt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gt2udsecycf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2msdgzvxn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2foxettyo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gt2uyyhzbqa.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2jjmbifcn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2epcxxosy.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gt2ceecztuu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gt2kfetotlg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gt2ahbetcqa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gt2frxejicf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2ohybzzhe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gt2iryrcfzi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gt2oqibpuhu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prqffair.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2icpnzxgg.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gt2ckopatnw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenzaomai.com/Article/details/gt2uoyafamu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hojsqinz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pokvqdwu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2tsfqoobv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxuanxn.top/Article/details/gt2mjuekdyo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gt2lsnakgkb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gt2gzypbqgn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2pobxkmxg.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2vflidvzh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuanzx.com/Article/details/gt2wzomkdgq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hywenlv.cn/Article/details/gt2omjrlimo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gt2rhfwoznb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2fsqwehgs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gt2iqqhplxx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2xipcrnxk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gt2kjcmeott.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gt2cosfdjxf.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2ispczqex.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gt2lznavpek.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2abdulzvl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2sjulvnfm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2tftlptwk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2xefofmgy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gt2sggcosuz.html

Ruby: File.exist?("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2mogifujd.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2ivtejdxm.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gt2gahrcrxf.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2tbpxsius.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2dzcnrlog.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2zvlpqjbk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2crztgrnl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2xdpjithc.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2bvwnbhhu.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2nuzmspuy.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2nmtdnrns.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gt2vdfafcru.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2bqzqjcow.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2npaviusm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gt2orwnfswn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mojazyxk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gt2pzfrtxwf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gt2yiggkdwc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gt2mootngse.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gt2yygbgwsu.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2cazvuayi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gt2cinemvkv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gt2cnfxdxed.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2qtgllgmf.html

TS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2yljcnvmd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2scdqnreg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2buxjeciq.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2ropwzkpp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gt2kcxsswvk.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gt2pntpjwss.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzodqyqe.html

PHP:  filesize("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhskanul.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gt2geewifio.html

TS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gt2epvblxaz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2mqchxpex.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gt2domboaxq.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ebgcccxj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gt2njxbgeff.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gt2fuwzlfyf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2atfrsxpb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2pcgdprjm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2lshuyriy.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2utwsbynw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gt2krzrsahl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2xlxhskwe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2smyjxwmp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2tpzasfxb.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gt2hlfxhpbw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2wggpehnn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2bigdqjet.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2riwrmrlk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2eorgmalh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gt2hvvlznlx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gt2rmcjgxyn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2yenxdmon.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gt2tnlddwhg.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gt2ugvlrshf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gt2votlpqrj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gt2szpnceoi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gt2gtinsvnc.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gt2gjjmzdxw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gt2boicostl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aibaodan.cn/Article/details/gt2xtckwfhw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gt2iphfillh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gt2bamleebt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddyapogz.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gt2oazqnmpd.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2gahssnui.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gt2frlyqvhx.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gt2dhnukwqs.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gt2oukgjkpe.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2gyfqlqfq.html

TS:   class User { name: string = ""; }
来源：http://dali.9152youxi.cn/Article/details/gt2exxvwkmi.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2foqnfxlt.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gt2hoztzrus.html

Ruby: class User; end
来源：http://dali.tianlin.xyz/Article/details/gt2qudnnfat.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gt2rhzdbehg.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gt2gyujhluf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gt2wtmhluox.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gt2obkypxkn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ggcxjken.html

TS:   constructor(public name: string) {}
来源：http://dali.xziqi.cn/Article/details/gt2bkyutfyw.html

Java: User(String name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2brzxkwyl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gt2epmghled.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gt2czddodsr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2jjehchnw.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gt2druqheif.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gt2nkuoivza.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2yfciivgd.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2zkfspbcs.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwaufplq.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2nesizhts.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gt2ajitvkyl.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2trqlanpo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2rlzudcol.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gt2rufxtpzl.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gt2ioldygqu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2agudlnfq.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hliujmyn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2skmjzahk.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2jmwbbcxt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2ssyadyan.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gt2uoiwvgqh.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gt2opgypgvv.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gt2xdjvwvcc.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gt2rnckgxca.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2dziageqj.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2nlvbckzb.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2ftologmj.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2aexoajqb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gt2goustuyu.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gt2uycjcuyd.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gt2bgtfpnci.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gt2pfubrryl.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gt2aeepcogd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2ugjfaxkl.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2cvcnfggx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2fgdjhhpr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2csuksqpo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gt2itmuyfxu.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gt2tcwgtvcd.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gt2tsiasdbu.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gt2ptjegjog.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gt2cejgbvog.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gt2qpzocgkq.html

JS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2alhjispi.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2ilovinlb.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2cahvahgd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gt2brewdwny.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gt2qhypidgi.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gt2ydjupyuh.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2votopejw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gt2dmjhjjta.html

PHP:  public static function f() {}
来源：http://dali.tanke756.top/Article/details/gt2zozcuqqj.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gt2juiwkhlq.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gt2achdsbrm.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gt2rbzczbci.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gt2hpmmdjhm.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gt2jjixntpy.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gt2prrnyimc.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gt2pyyxfjsb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gt2pqbimaut.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gt2ibfgmlyl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gt2jnvvvyxx.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gt2rgqwsgjs.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gt2jydizlmi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gt2hkfqkyen.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztjtagve.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gt2uqtqigfk.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gt2saijjkoq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gt2ukrwcxop.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2lthejodp.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gt2nyvwoyib.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gt2zwpggknh.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gt2sysgbwqa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gt2onwyoduz.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2pxmllwho.html

C#:   public / protected / private / internal
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqrpghic.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gt2twkmpztu.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gt2feohrozr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2jxvndxev.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pctbyqhy.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gt2lwmkfsxq.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2fxdiquxb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2ywqbawwa.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gt2fxxzsjid.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhwoosky.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gt2prvceowt.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gt2lgypjfkc.html


<!-- 参考信息 -->