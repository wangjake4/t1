代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gt2fzuthgmf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shuidangran.top/Article/details/gt2qnbllzcc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2ubhxjfve.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fzxfessc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wzedklej.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gt2mthumzyu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gt2dqptnvro.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yvedp.cn/Article/details/gt2rmliieil.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxuanxn.top/Article/details/gt2vgtxetpy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2pwbipbrm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxiehclf.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2rwmoxhsf.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gt2zmrsbpfq.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gt2uetipcbd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gt2nsnrynkr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqdhqawx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gt2eyqrfmxk.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gt2bzsdgvtz.html

Py:   s[::-1]
来源：http://dali.316326.xyz/Article/details/gt2kxoqxfuz.html

PHP:  strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gt2apmbwuqw.html

JS:   [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gt2uvyadhza.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szbntvvq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2comvvbnu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gt2lnplxdhd.html

Ruby: s.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2jsnrnfno.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gt2rzefymdh.html

[E12] 统计某字符出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2jqofegqn.html

Py:   s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gt2dqlisspx.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gt2meyqhpht.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2cderphex.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gt2rpnenvel.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gt2ihxtasuo.html

Go:   strings.Count(s, "a")
来源：http://dali.yueranfly.top/Article/details/gt2jgaagolg.html

Ruby: s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2brakbzdk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gt2ovdpoeva.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gt2xkmpexvi.html

Py:   for ch in s: print(ch)
来源：http://dali.cdnleiting.top/Article/details/gt2dbogrwgb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gt2qdykzpvn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2qyexkmuz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2tdyhhwpq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2abvxxtnv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2vjfnmzco.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gt2buoddprf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2qtowredq.html

[E14] URL 编码与 Base64
来源：http://dali.hfpthk.cn/Article/details/gt2kyfhhrmu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gt2kfvcyhtt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gt2niyklfha.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vorxyplo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gt2lqdkujji.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vttzagwq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gt2mwmqizzq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tuqqlexx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fengsongda.top/Article/details/gt2iqzjqcbf.html

[E15] HTML 转义 / 反转义
来源：http://dali.shangyingyoupin.top/Article/details/gt2spuupwgf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gt2wolmqfmb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gt2csxxyuib.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jianghu66.top/Article/details/gt2rgamrruu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gt2piygzmuf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sysykeji.top/Article/details/gt2xwricyuz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aizwys.cn/Article/details/gt2hhzgkizd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gt2guzeqatc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gt2bdoypxnb.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gt2xnbihmbl.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gt2djubprug.html

PHP:  number_format(1234567);
来源：http://dali.yj20258888.top/Article/details/gt2wqeneqov.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gt2vshrzenf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gt2udkemedo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2alwrajrs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbeeqvlu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gt2qvkkptrk.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gt2qywghrzn.html

[E17] 首字母大写
来源：http://dali.yonumen.top/Article/details/gt2jpwoogof.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gt2bsnavvgy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2pvecjlzi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2debeijlw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gt2kvfdvtsw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cqqwz.cn/Article/details/gt2zywlajzi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2ijfbunjh.html

Ruby: s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwphkdqr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gt2foeqmajd.html

[E18] 模板占位符替换
来源：http://dali.wangdashe.top/Article/details/gt2oxinrkpi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gt2ksdkrxvs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dashuyun.cn/Article/details/gt2shigrocj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqplkbcj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2dgoatind.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2scvchmzh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2kgeqfabp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gt2apftgfii.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gt2odkkzchv.html

[E19] 多行文本按行拆分
来源：http://dali.hfpthk.cn/Article/details/gt2olvmhpsw.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gt2tdzlxnmh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2jlrpofhc.html

JS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gt2ppaucgzv.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gt2gmorzypb.html

Java: s.lines().toList()
来源：http://dali.yuxming.cn/Article/details/gt2lublbyng.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gt2imnmxinb.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gt2bwxdbqcr.html

C#:   s.Split('\n')
来源：http://dali.dashuyun.cn/Article/details/gt2fhgaupvs.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258.top/Article/details/gt2quxbkryw.html

Py:   if not s:
来源：http://dali.dashuyun.cn/Article/details/gt2jqrrpgkg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.feifeiyinyue.top/Article/details/gt2cndmrcfm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gt2uasgnhbn.html

TS:   if (s === "") {}
来源：http://dali.ivvv.top/Article/details/gt2xmetozit.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gt2cprjqqgz.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gt2vwcbislb.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gt2dbipqqjn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gt2oukvoidd.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gt2uxwpfpcy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gt2wleuiomp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.meibo888.top/Article/details/gt2duvicifs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2vthmsymk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2wnwrijsl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2nzfrirct.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zdqjudy.top/Article/details/gt2jdiujbqs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2aymcpoiy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2hjhaojsf.html

[E22] 字节长度与字符长度
来源：http://dali.hnxiangtu.top/Article/details/gt2tlfwywab.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gt2gtgvralf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2dtxsqvzx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2mhpllsfx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gt2cxgtmjci.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gt2yuzhybbb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fzhhl.top/Article/details/gt2gdpthlyd.html

Ruby: s.bytesize;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2swkuxkbb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gt2mzovyeeg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2tznqzuxs.html

F. 文件与目录
来源：http://dali.haohaochexian.top/Article/details/gt2qsmorcce.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2bgpkkokl.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gt2kftzftfn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gt2cehpzqwk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2tiqdxsyb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gt2bzowwzez.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2dzhxdmrq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2rpchviei.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tianlin.xyz/Article/details/gt2yvargnku.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2cisyyjhw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2ixshrzra.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gt2irgkbkyg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gt2ctpbngiw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gt2auavlmqh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2dwvzxext.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqiwzeyg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gt2wkwyjvbv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gt2sqynqfst.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gt2omoovbio.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gt2qaomejra.html

[F03] 写入文件（覆盖）
来源：http://dali.hammf.cn/Article/details/gt2yydehpiy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gt2ndrrzzad.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmxssrfu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gt2cxwdekdq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2dohqyxjr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gt2pvhzwcdr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvhfcjlm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pitfzyrt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gt2fdobmuzu.html

[F04] 追加写入文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbjltcez.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pnpbyqxz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gt2mgwhohci.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2juqaisse.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2bwifqwwt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gt2zmyoitti.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gt2ethkzaeh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cdnleiting.top/Article/details/gt2rozluznd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dashuyun.cn/Article/details/gt2vdgjozhx.html

[F05] 判断文件或目录是否存在
来源：http://dali.sweek.top/Article/details/gt2hbgyshog.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjtgiynq.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2afudmkuw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2gyrwogjw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2ixxxergq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2puzhprhz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gt2dfqnrdlf.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2pznuryja.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2wthsdcot.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gt2napsrshc.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2pratpymm.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2seauxlvu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2nfwuycyw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2amwjcjzg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2wawjizml.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2mlekrdmb.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2lsgdycir.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2igwxsylz.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygwvbefi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gt2iblzttln.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2yzklkxvn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gt2pyczcbdq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxklmjdl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gt2efgwwzjr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gt2hcsjfvur.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gt2mtujgznp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.iojbl.cn/Article/details/gt2hmfbtcjg.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2lanyeziv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gt2akvpemtl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cucudq.cn/Article/details/gt2bdeaxpbu.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2ohyzmbqs.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gt2wvqdqboa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gt2wwankmec.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gt2dokvygrp.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gt2qfgvjjqy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2cxecefqz.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gt2ovmrzajq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2cyxadssw.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2fbtsyjys.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2yzhxhnxs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gt2ouosdxyp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2qwgahyqa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gt2beddcvcl.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2dlmiyvbi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gt2wudbtrjx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guowangkeji.top/Article/details/gt2byqsobxh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2yoierjzx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2pxvkrcng.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2wlfvzaiy.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2eqpdtewx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gt2ckmzeniu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2lpszwzno.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2xklnovry.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2kklvitxx.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gt2pasjazsj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2llmlengb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2mhzcjjcf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdfynavf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2ywfpmoqa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2eqzqccsg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gt2jndtlprz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2qaincpxm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hywenlv.cn/Article/details/gt2zsxueoxe.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gt2jeelthcq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gt2wlyqmiea.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gt2ewuwsiif.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gt2uqubnryx.html

TS:   // 同上
来源：http://dali.c1oappe.top/Article/details/gt2drniuwke.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shuidangran.top/Article/details/gt2qboellgb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dashuyun.cn/Article/details/gt2mjieukha.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ecdqdhxq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gt2uetnylri.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2rnszequn.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gt2wywgnaqu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2emtyfrns.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gt2shzhovmt.html

Py:   class User: pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxjetkwz.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gt2wycebsey.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2xyippfsq.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gt2ctlkfukr.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gt2vxuiwhxy.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gt2cqoqgoxr.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gt2zpxitrhz.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2iqolkwhi.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gt2prgcvefw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gt2fhdtrbic.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gt2ddcrcipo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2kbbbzbyv.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gt2xrvunjhk.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2kewuedee.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gt2jazwygwb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gt2rzrmydii.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2sfxgejqo.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2kfdeyinh.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2npguzgdw.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqhmtthe.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2nufyhqzh.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2ihkoakbf.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gt2fzaebtes.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gt2qjbveyah.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gt2lnilhtmb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iilflvxf.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gt2qqbabyzt.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2wesebtiy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2fagqffmy.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2gjcedjca.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2qqqofcuh.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2oxhkiszk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2dciexcor.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gt2mvkrqnrf.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2jvfhberv.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gt2cdcwsini.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gt2jlexwuat.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2psuomfts.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2piijvgqe.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2jgpkevke.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2eyfubkfq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gt2yfkvbixj.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gt2giqjqiey.html

C#:   class Admin : User {}
来源：http://dali.yj202588.top/Article/details/gt2jtkeyjwp.html

[G06] 重写方法
来源：http://dali.ehwqpu.com/Article/details/gt2sfgcdtrb.html

Py:   def greet(self): return "admin"
来源：http://dali.daxiang520.top/Article/details/gt2kxgetgch.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2ocbdasha.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2jdekuvuh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2vgxykcli.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2lxixnvzv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gt2bxogstqj.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gt2cmaifbbv.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gt2xehobhpb.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gt2nufpldvc.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gt2imasqdtj.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gt2zijfwihz.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2pnkutwet.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gt2ojrchaai.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2vtdqxteu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gt2bnsrrhez.html


<!-- 参考信息 -->