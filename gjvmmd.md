代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ybcxt.top/Article/details/gt2ufpxfzdu.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gt2hcdmreaj.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2osryrnil.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gt2ekurzyis.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xozubiqo.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2ljeuwuuk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nwbrower.top/Article/details/gt2pvhcuuzf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2xpkrbqpw.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2etxcbycq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gt2endbbkdt.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gt2fgwahtve.html

Py:   s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2tauvgedu.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gt2nsoxzcfk.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmeipyqf.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gt2tzhxpilx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gzhubu.top/Article/details/gt2ryfharwk.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gt2pneyxchp.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gt2auyrfgzi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.birdmap.top/Article/details/gt2krlpiitt.html

[E13] 逐字符遍历
来源：http://dali.hfpthk.cn/Article/details/gt2tgrcfgnx.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gt2tawcqutx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cashguo.top/Article/details/gt2vnkunrjj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2yyulufsb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovbtqefn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2hlsnfsgs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gt2mqkmwcwv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gt2pkhbxapq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2jwethnvb.html

[E14] URL 编码与 Base64
来源：http://dali.birdmap.top/Article/details/gt2uablddwh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gt2avjzgvfw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzpncsga.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gt2vyochreu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aizwys.cn/Article/details/gt2jfetaxqt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cymuepbn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.redwolf501.top/Article/details/gt2hibqhggf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gt2aiklyfys.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xinyue.icu/Article/details/gt2ksdogkhi.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2moqrbjxv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gt2jgxjmtta.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzacsixr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ntjyqjjn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gt2mpxotlap.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gt2pfhjxooe.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrsuuon.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.svipenyu.cn/Article/details/gt2rfbnldqk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2aahbgotd.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tclqqtuw.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gt2pctskuzg.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gt2rsccrlfc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfixpggq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olnyhmmy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gt2xznrcwfa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.quarkkingdee.top/Article/details/gt2fupbymmf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuxming.cn/Article/details/gt2zmcdjijn.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gt2qillczsu.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gt2jwtqtiaj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gt2nwnpvwlv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gt2ygpcrozx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpsmrkpl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftajexys.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gt2xmejgldr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gt2pjjknlxu.html

Ruby: s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gt2lysxymtm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhixingplan.top/Article/details/gt2veshxoxn.html

[E18] 模板占位符替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpcslozl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ipxfujxp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cashguo.top/Article/details/gt2qdjassrg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2gwbbczqz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2xjhqinoy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2oinxtmjg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2nnsgrmog.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exoozfgy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxygicgk.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gt2tfbpbvld.html

Py:   s.splitlines()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yneidzqe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2vftphyte.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljzfghul.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gt2rugsshxz.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gt2rslxcrjg.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gt2dquyifsf.html

Ruby: s.lines
来源：http://dali.cheryme.top/Article/details/gt2ifqcpzvi.html

C#:   s.Split('\n')
来源：http://dali.sxryk.cn/Article/details/gt2tkwubinb.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csqvtegc.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gt2avceuleh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gt2bszyszzm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2kxnpvbxy.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gt2vsprynld.html

Java: if (s.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gt2xwikswlc.html

Go:   if s == "" {}
来源：http://dali.xziqi.cn/Article/details/gt2uphduvrl.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebtaazzw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sufxvd.cn/Article/details/gt2vrbzdzei.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gt2iuwttlln.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gt2gdzhoqhh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2yagzyehj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2ymapkkow.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2rfoalkjj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2drdbcajw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigfzy.top/Article/details/gt2gvtasncj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2mzljxuud.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2qcbxqojk.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxmzyptb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.andypj.xyz/Article/details/gt2vutcdgnj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2vizreryb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2vegvlbje.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2ufkhsjgt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ivvv.top/Article/details/gt2swesabos.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jianghu66.top/Article/details/gt2hltvzhbr.html

Ruby: s.bytesize;  s.length
来源：http://dali.iojbl.cn/Article/details/gt2gbbeccdc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgdtccn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2nrowwouc.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gt2qdwappih.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2qfzbzhqb.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gt2fchqiikd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gt2aefquzye.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2rstzmzmn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gt2hibhcuxy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbvmdsei.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2tddstucz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gt2pqqlwerx.html

Ruby: File.read("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2wkusgjtw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2tkjxvfhw.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gt2rdizpsou.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gt2mxqgkxab.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gt2dokuydkn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gt2kfwadtbn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlpbgwab.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2pfmssbdb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gt2gssyzntu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gt2ubjsurmt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gt2zzdkokfg.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gt2kieuihao.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2esbwymjs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gt2uzzxetfo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vudbqdkl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gt2pagomlin.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2kbpvfexk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gt2hbwchjtr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gt2dvoffdbo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2ximqagma.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gt2qtsikuwu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuxming.cn/Article/details/gt2wxdvvkny.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gt2zkuwjtkc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2cwinqats.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2eusccepu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gt2eijprude.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gt2iktfnwdd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2aofoppjd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.haohaochexian.top/Article/details/gt2lbsjdefc.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnskcuzf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gt2atixjwxn.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upgjunrc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2vqvnogsf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2tzgbtqjo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2qbnmwivc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gt2yuzqyyph.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2jghzolcf.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2apeqolot.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gt2ruutnhoe.html

Py:   os.remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2knljjpop.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfthakkq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2xztxehua.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2dsidhcyl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2xkbqrixs.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2sedzzxdw.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2fgsxndjb.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2avsiyrke.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gt2mhigqnfj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gt2gnzznjbi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gt2ltvxqhbp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gt2qdxesuag.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2znaniatc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gt2fphrtzkw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gt2gmvcilyy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gt2cwcshnrj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gt2xpewjbxe.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gt2qmdninqd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gt2xhdgrcgr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gt2luqnlbtv.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2bfreclyq.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2bfthidzd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gt2vicsqnjl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2flsapfhr.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gt2jnkkfuom.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2slfhxsrg.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gt2ixhtekwv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2vxsozneh.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2ophbqpfw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gt2meailect.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2stpwjbfh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2cvzglbbs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gt2ogppadfq.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2ysinkmik.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gt2ylmanosm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gt2slblrmrj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2bxqqwzza.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2mbmhyest.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2hwiwtnfi.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2yvvxgfwo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gt2yvldfwlu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2akboipou.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2aopzjssi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dwxmfmbq.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gt2fkovdfep.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2sgouwvhl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gt2vhfdhvsa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2pkqnmzwv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2esqqgzsd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gt2txkwiuhu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gt2datkrmhk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2cloqudtd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gt2rzouueia.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gt2xgfigbda.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gt2jwwxbbya.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fzhhl.top/Article/details/gt2wjkkeiqr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gt2vzaxfopq.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gt2ysyofour.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gt2agmtvzzq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gt2nflrfazh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gt2telpdtjo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gt2zbpkxhuz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2wmsnwafy.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gt2jkyerkjj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2rhtdists.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndpiavpm.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gt2miqihbqs.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2omvpryay.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2agzowfua.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcrpqear.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2mhxxxpkg.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gt2fmzibvem.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gt2lppbnlri.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gt2zraahdei.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2utisrdoj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gt2eyxmwkzz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2uqpessgj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2hkpokyub.html

TS:   constructor(public name: string) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2llsbgdqp.html

Java: User(String name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2gxgfwiku.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnkrkogd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gt2tfjjflfo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2qaepmfzf.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gt2scqzrqtx.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2fhitdajc.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2deiypwiu.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icbxnual.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2ijfzqztk.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gt2bflfadnt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gt2celsbnvv.html

Ruby: @name = "x"
来源：http://dali.jyoumei.cn/Article/details/gt2ewvqjort.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2wcagqpnm.html

[G04] 定义方法
来源：http://dali.guowangkeji.top/Article/details/gt2rsqjuzzt.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gt2eurtwcrl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2kbzroccs.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2srtodgvw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2xmsbjqla.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2wjqmzeyx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2pnzaynwr.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gt2eptyxwqa.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxbrklxa.html

[G05] 继承
来源：http://dali.316326.xyz/Article/details/gt2dkmilior.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gt2tafbifkp.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2mjbeyuxa.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2vrmmannz.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2wjzrgyxh.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2uhbeenyj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gt2ytwdappu.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2naaprykw.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gt2tfhvmrla.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2psnqimex.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gt2ncumuykh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2qnugeaxn.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2fmseekkj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2farahjej.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2syddmtak.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gt2ryovivfs.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gt2yxxgokgs.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gt2eaggisgv.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gt2wuusnime.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gt2ybhgiiqc.html

PHP:  parent::greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2unvzrktq.html

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2zqjenson.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2vqrpvivj.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2nfhxjgra.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gt2voxahkae.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gt2lijvueyu.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2zaetppfv.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gt2bpobjwpn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gt2uwqeiaav.html

PHP:  public static function f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2qstwaxwx.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elynyipp.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gt2izdmstnr.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gt2adnhqstk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gt2bbznjvue.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gt2qprhtgxl.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gt2tqrwwiwh.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gt2nrexkjag.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnqzz.top/Article/details/gt2tpqtgtir.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gt2vjbomeai.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gt2eygilgig.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gt2aejjmjpv.html


<!-- 参考信息 -->