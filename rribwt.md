代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.nwbrower.top/Article/details/gt2wmgbdvxn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.havefunace.top/Article/details/gt2ujgepeao.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gt2zgikoclh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuxming.cn/Article/details/gt2kgybents.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cashguo.top/Article/details/gt2cuginipq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2cgdircbk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gt2ycqfbnky.html

JS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2qamhttuc.html

TS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2lgepcnes.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gt2gqkutdoi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2inzqrhov.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gt2ttznhgvo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gt2qefbqlac.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gt2fxiutqhu.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gt2zafflgsa.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gt2pggquprk.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynifjatz.html

TS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqxjntkj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gt2vvtpfzct.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gt2xdfxyftk.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2twvzdmmv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gt2srfkybuh.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gt2usraviju.html

Py:   s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2tqgcqvmu.html

PHP:  substr_count($s, "a");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nlwyajrv.html

JS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gt2rfqmhwck.html

TS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gt2bbmlolqx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gt2iepujqgd.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gt2knpnnohm.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fnkvdoee.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gt2uvkswudh.html

[E13] 逐字符遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2egtxkwlh.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gt2zsafnfrv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qocfxicq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2fptheyru.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2rvdiivnr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2fzrfcuzd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2paptidlz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgufenzy.top/Article/details/gt2meitzqpz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2nyvukxln.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxilohtr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.9152youxi.cn/Article/details/gt2vkfuduue.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gt2qbgpesvt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gt2qnudxdqf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hfpthk.cn/Article/details/gt2lumlettj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftapwnai.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gt2oiouygqw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gt2fsxdppvi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2ntmhrsae.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gt2yiupbusf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.andypj.xyz/Article/details/gt2sxkmzzna.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gt2vjzjkeek.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2igedlzwd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.birdmap.top/Article/details/gt2zskdwnlx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gt2rtvbofgp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2jmmhwkwp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hcmtyrvj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gt2fxfjmuhs.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gt2sifhvacx.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gt2weodromb.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gt2lozthotc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcupozeg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxinvctj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gt2ubkwwtce.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gt2tjihtpbz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gt2tuwysusi.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gt2qlyfmzmd.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gt2unyzimfl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gt2zeaebgll.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cashguo.top/Article/details/gt2zfptvttv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gt2nopcmpri.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2fboeqzoi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gt2ianwzgfs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkqglmo.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jcuizbvs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gt2ovredhal.html

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gt2ftgtlfcd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gt2ovyvaosl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gt2kkualgds.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2fuzeifut.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2bvufqpbu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2yqbzpzhp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vyhxsvvw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gt2nxytxyyd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gt2gqkowzlp.html

[E19] 多行文本按行拆分
来源：http://dali.zdqjudy.top/Article/details/gt2ixhqhrja.html

Py:   s.splitlines()
来源：http://dali.birdmap.top/Article/details/gt2nlenzmix.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2levzifjo.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gt2pqnvcbdk.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gt2bxwfbrky.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gt2xsrljpmj.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gt2wfcbffnb.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gt2lkgplbwu.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gt2cuokagki.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gt2mieqztrc.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gt2cstnllon.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jiagoushi.top/Article/details/gt2ehnotoln.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gt2bmzjxlxw.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gt2rcvczcqq.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gt2hazlfgqk.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gt2qnndeajt.html

Ruby: if s.empty?
来源：http://dali.hnxiangtu.top/Article/details/gt2rlnzxevw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gt2mcsdurbw.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gt2vsmpivvv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gt2iihwobrh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2ewlaqouu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2scjombby.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2evgufkal.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2rlwlggtk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gt2ipjyzpnt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfhhhgca.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2jaieticy.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gt2yrftghxr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gt2olhpaueq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2snzjhqbp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddmbvdwj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2etobzxtb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gt2mrokvqvz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuetiantiany.cn/Article/details/gt2vveqdpnq.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2vgtceeno.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gt2lihjvknl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2utzihley.html

F. 文件与目录
来源：http://dali.jinqigfzy.top/Article/details/gt2wwftwlmn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2xvxffbtk.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gt2nlixtfsk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gt2vgcijfyl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oiqsmnra.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dltsnqnh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2qgntipct.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2xhcnxfpq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gt2ohppqnsy.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2aofnjjvv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2djaryoce.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gt2esatlliu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zycfv.cn/Article/details/gt2dtookjde.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydxvprsy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gt2hiahazhu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gt2bfxdcrhj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gt2qyaxiqax.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gt2hpogaxmh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtsnyfaw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gt2yroqqlsg.html

[F03] 写入文件（覆盖）
来源：http://dali.shuidangran.top/Article/details/gt2xfmouspr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gt2nryehjre.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2nevlwzjn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2stucwvma.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2oclpuspm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gt2naersoyj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gt2bocfegel.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gt2qvfnayah.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2jwacluxt.html

[F04] 追加写入文件
来源：http://dali.zdqjudy.top/Article/details/gt2flmhxbkz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gt2obkttsqq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yangfankeji.com/Article/details/gt2ypxyqemh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2utrmvxnf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2nkkdgyqn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gt2hjskhpab.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sxryk.cn/Article/details/gt2ifprbouj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gt2gohireiy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.kuanghao11.cn/Article/details/gt2hzgtltwz.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gt2xydsgscr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxuanxn.top/Article/details/gt2mufohjuu.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2sthbzgbh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2bfbmnaxb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2dnmxcnsl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yosnzkxb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gt2neqfoclq.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkwreiyq.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2awwzgweg.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gt2qdholpyb.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xudnftlt.html

PHP:  unlink("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2tboeyocv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2vawaxnfw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2ukrckkvf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2bigcvpwn.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2nuzjfaog.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2gzikauep.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gt2pntsamnc.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gt2vvfdjrwi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2fvxbrmgi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2jvwbsxhf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gt2sgyltxos.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gt2uexcjyug.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gt2jciokvzl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gt2gplhbqeo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnxiangtu.top/Article/details/gt2zoedysqz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gt2zjensjxt.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gt2qytjtxub.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gaohongyu789.top/Article/details/gt2ldzkcnkj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gt2cwfkbmjf.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gt2bbrjippk.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2hzlncmll.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gt2ojhfllyc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2actylmrk.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gt2pkivjmah.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gt2daahiucj.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gt2jspvnkfe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkwuvbff.html

PHP:  filesize("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2fqdsdbvm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2lgtkgihm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2qxuqezbc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2mnotxplt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gt2kmrfckbi.html

Ruby: File.size("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbwhusdf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gt2refzzvbs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gt2nxmucvco.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2mrqfvxvy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yzweeemr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2eaetkegl.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2sjezvyag.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gt2btjmprpa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2yrugbdjc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2byntrnza.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2ggbyzfcw.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gt2izujoyws.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2rysvqcbb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gt2mlkijzvt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2awcarvlv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2wfdemqzj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvdsorod.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gt2mnonjydx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2vchtywcu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wiklskey.html

[F12] CSV 读写
来源：http://dali.0kj1m.cn/Article/details/gt2kigkfevk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmunzrvd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gt2ildgkqnj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urncwhqv.html

TS:   // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gt2oggkakhu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gt2ckkcudbx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gt2ccwipfdr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cucudq.cn/Article/details/gt2ldfpevvj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gt2zeywjopz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2kajardtb.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gt2clfankhs.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ecpwrnhc.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gt2lmbydqyu.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gt2ccappekn.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gt2vugrotui.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gt2jbuvtxky.html

TS:   class User { name: string = ""; }
来源：http://dali.bjfxy.top/Article/details/gt2hgnfylaz.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gt2bxadqsfg.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gt2hjqwkfsj.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gt2nfgwszza.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2kqxielrc.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujwrvmkk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnvplztf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gt2wirbpaiv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2ydrfhddg.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gt2lbfnwami.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2vvsgbppl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gt2psmkrwks.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gt2gydfrcan.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwxfeqpo.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gt2nbvdwnhy.html

Py:   self.name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2flmjwozs.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2eivegzln.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gt2kkfkqekg.html

TS:   name: string = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mjsdntig.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gt2bcinembb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gt2woyveckk.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2xleilvow.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2pgkrteqh.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gt2uqzmfeds.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gt2froeqllt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2rpgavkff.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2yfigijre.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2cevzfxwl.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2kknwzhhg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gt2pzrzlinm.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2lnyjlsao.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gt2mznjivfb.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gt2taclatgc.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gt2qtheooml.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2simdogdd.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2kbppwchf.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2iywgofkw.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukpbrrgg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gt2kumbrgsn.html

Ruby: class Admin < User; end
来源：http://dali.gaohongyu789.top/Article/details/gt2ojhlxivh.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gt2bvptrryz.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gt2kkjomwag.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gt2gwzsgowg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2lknvgocb.html

JS:   greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2uwiehtgz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2katxbgxu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2qdpsnlaa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gt2hzqolqql.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gt2axptbbjh.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gt2mmiaximg.html

[G07] 调用父类方法
来源：http://dali.cucudq.cn/Article/details/gt2zifgftef.html

Py:   super().greet()
来源：http://dali.sxryk.cn/Article/details/gt2fzmtkqpt.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gt2vfbkkqkq.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2ltznxsmy.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2mvvlqqhq.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2qgnywiub.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.iojbl.cn/Article/details/gt2mvykdwsi.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gt2hmdkfsyl.html

C#:   base.Greet();
来源：http://dali.zycfv.cn/Article/details/gt2tzwolsjm.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gt2cwgnhqjn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gt2dwdnqgdu.html


<!-- 参考信息 -->