代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtnueauacf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtzotwnhty.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtbhanywez.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtfcappqae.html

C#:   s.Replace("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizqeawrr.html

[E07] 按分隔符拆分
来源：http://dali.havefunace.top/Article/details/gtuilxjsfq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gogol.net.cn/Article/details/gtxgxmvfhh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtqqceelvk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gtsoccoftu.html

TS:   s.split(",")
来源：http://dali.guannengcc.top/Article/details/gtknuwvvqp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gtxxqnbznt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtqkkdbqap.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gtelgzdpaj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dashuyun.cn/Article/details/gtpjszgqed.html

[E08] 数组按分隔符合并
来源：http://dali.jianghu66.top/Article/details/gtmubqsoeu.html

Py:   ",".join(items)
来源：http://dali.xuetiantiany.cn/Article/details/gtbiybsgdd.html

PHP:  implode(",", $items);
来源：http://dali.pycfn.com/Article/details/gtxmnzvyrd.html

JS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtynujtkbp.html

TS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtpjmfepqx.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtfhvwvysr.html

Go:   strings.Join(items, ",")
来源：http://dali.hongshengwenyu.top/Article/details/gthzrqkofd.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavfqurra.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtgsjgltno.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gtazrxpndi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.iojbl.cn/Article/details/gtmdulzjxo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258888.top/Article/details/gtyzmzmwlc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtwcjhzxls.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtyzssqnqn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtmqaggzmg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtemheroyk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zdqjudy.top/Article/details/gtyvomunij.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tanke756.top/Article/details/gtvefaivfu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gzhubu.top/Article/details/gtqgtubuid.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sweek.top/Article/details/gtkiemyfol.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnftepxuc.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtmbuxqvmm.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtnxuwowsg.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtzolghpdr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtvtmbvxgh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtmzobpune.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gtbenmswwr.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtuffkmgyy.html

Py:   s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtghvmzoen.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtdbdonvjt.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtjbgbicwr.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gthrfbigqk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gtconhthmt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtqfdlxpud.html

Ruby: s.reverse
来源：http://dali.mhx1999.top/Article/details/gtdumjnuzv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtcnkrrugi.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtopgiesvy.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqxrlvrt.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtbxrnyxxm.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtspuzixoq.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gtnafjwjwz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.vqdsnc.cn/Article/details/gtpobzjrld.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gtmnwfluja.html

Ruby: s.count("a")
来源：http://dali.cucudq.cn/Article/details/gtxrlueibw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtyqfefrof.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gtqkiuyobb.html

Py:   for ch in s: print(ch)
来源：http://dali.sysykeji.top/Article/details/gtetfdyabk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.mhx1999.top/Article/details/gtbveagake.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtrulgoocv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtgqknaoce.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtrrmfanzc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtjjbrgyjo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gtpghmwnjz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hammf.cn/Article/details/gtncgwelac.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gttvhpsbqe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gtvyjfockk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gtknacnkkr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gtonxxgrzn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtivwruvkf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gtjmrjkipk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gtjlvxwxlr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gtyylhwsck.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtxfducluw.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gtcmezikpt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gtevutvrkq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvwahxbe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtyguhkfrv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gtxdazjfaw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gtawufjldh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cheryme.top/Article/details/gtphcjmdca.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqrownzc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yangfankeji.com/Article/details/gtojdtmcwh.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gtfswnbxrn.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gtpfagobzs.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gtlrhwhtno.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtbsbmzwbx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gttitwutrp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gtbqiffeqv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gtwhptosqv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gtojobmpqo.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gttvczhpuj.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gtrxkziyvr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gthikfagib.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gtciijxnjk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gtyjsavnlu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtaktwszax.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtljjjtrrg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtmfivvgml.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gtgvfoistn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gtddpypenz.html

[E18] 模板占位符替换
来源：http://dali.9152youxi.cn/Article/details/gttsswkwvb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sufxvd.cn/Article/details/gtqumjnhzp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzezewlus.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtloarcbfk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtmxrmbwmv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtngunfgqj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtjkrfdgcm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gtdfecfhvu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gtgydvyhba.html

[E19] 多行文本按行拆分
来源：http://dali.gogol.net.cn/Article/details/gtvvgleadl.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gtqaoufmzn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtrcboglyb.html

JS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gtnnnszmdy.html

TS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtzzeglzfj.html

Java: s.lines().toList()
来源：http://dali.yuxming.cn/Article/details/gtrxrfriza.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbkeyroj.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxizohav.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gtpjisyrqx.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gtuclnpcrl.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gtbjvbcssu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gtjrslnltd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gtnzeczjmz.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gtifdtjxsa.html

Java: if (s.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtcjgadjsb.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gtllnocsuy.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gtlzdjqphy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtswbuylnm.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gthghluulg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gtbhxmpvkl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gthxrxzapa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtaokghlkk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtljpowcoq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtsxbedder.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gtwnurvpxm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtukoxhkmi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtshgemidp.html

[E22] 字节长度与字符长度
来源：http://dali.snrcjt.cn/Article/details/gtvmcsifmp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guowangkeji.top/Article/details/gtgccwmsub.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtyvbrtzje.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtureiagxe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gttnxkhlcg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtlpyyjdzl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gthpkrykwy.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtjfgbxuid.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdzfbqzm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gthmihqtbi.html

F. 文件与目录
来源：http://dali.andypj.xyz/Article/details/gtidclnyty.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtimbhnosd.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtlpjaomdm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guowangkeji.top/Article/details/gtfnjxprxo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtkiaiutmp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gtfotuijur.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtiddimbkt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtijthcqqo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gtnbtobcsv.html

Ruby: File.read("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtsvqyijbk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtcxbhmkvt.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtdbffxdof.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tian-w.cn/Article/details/gtoyhqveml.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gotoacloud.top/Article/details/gtbgjubkds.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gttbwpeoug.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxrjfedlp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtaeevlimq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jiagoushi.top/Article/details/gtdnwyehij.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gtuzjxcztn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.redwolf501.top/Article/details/gtgqbvmfhz.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gtckoeirqg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtlfggtcfw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtjhelxcgl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtphgyxxjv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtaaqjkdss.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gtepajvgly.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gtnemfhjfk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gtqwzihkxr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtsrzjlxoa.html

[F04] 追加写入文件
来源：http://dali.cashguo.top/Article/details/gtfnvyzvyt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtonoyvobc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabpnqkke.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtxoobzjjt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtbmhytvst.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gteihgxarh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sysykeji.top/Article/details/gtcypisqfp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtmgniepox.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gtymhluysx.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtqcygcxfn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gtsswjomgx.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtakwqmttn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtfnxsrkgb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtbeszjoux.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtcdxgueld.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gtajmpgwyn.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtuirebdsf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdslwftc.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gtzivgbmqc.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtpralglyo.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtwobqgoqm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtdheyuhdy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtqtbxjkqs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtkhrgifnn.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtfvesfuiz.html

Ruby: File.delete("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gttsbgvbrc.html

C#:   File.Delete("a.txt");
来源：http://dali.yj202588.top/Article/details/gtakuyrric.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gtslybbowy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gtjclovyxl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitkdktly.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtrtlzmejo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtotzqdjet.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxinkj.top/Article/details/gtywjdxhnx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtiwyhinpy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gtlandnvxx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtmdvluehd.html

[F08] 遍历目录
来源：http://dali.hongshengwenyu.top/Article/details/gtjyguefrp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.svipenyu.cn/Article/details/gtjbgwenzf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhengqikj.top/Article/details/gtgclwkmlm.html

JS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtlccwtkqd.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtulmiujik.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtjenjifet.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gtwxewnkdx.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gtrlfizxtu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtmgwnqqvz.html

[F09] 获取文件大小
来源：http://dali.iojbl.cn/Article/details/gtfdvycuem.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtnevphbdu.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gtswsfyydn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtysqdmnug.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtpvvtstnn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtepudleac.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgllpkctf.html

Ruby: File.size("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gthrbclhwi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtciyqtzfr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ehwqpu.com/Article/details/gtkguxgueg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtefrbimxi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gtiprhvvua.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtbkckyqzd.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtcttaneqz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gtssvyzbqk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtufcnwnsc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtakpwpdpo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtbwxewecw.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gthpvsxgws.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtkbgxhqoa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtxyjhaplf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtlmnzeadx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtfsqevcdu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gtjgihcrpk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gtrcleczqy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtwkyinhxk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gtpuylzlkj.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gtpqkzqjtp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gtwxfhbvlv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnefxwic.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtscgpjrui.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtodznvcyk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gtijozrrax.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtpxtdxtnl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gtleorogrd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gttftbgcru.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfixsqwgb.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gtsvnlsqzq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttefbpmaw.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gtbmnkvsqy.html

Py:   class User: pass
来源：http://dali.xziqi.cn/Article/details/gtavhqtynn.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gtdxeautic.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtornlmobb.html

TS:   class User { name: string = ""; }
来源：http://dali.aibaodan.cn/Article/details/gtalabytxp.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gtbykkpptd.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gtijkfrwyr.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gtmangcfsx.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfascmhhw.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gtszaofhsg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gtzdcqlnbo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gttihufute.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtgxemlduh.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gtqcfoultd.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtuewqotgr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gtoirlefjp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gtpfhgbpqd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtatdyhofe.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gtzrlourqd.html

Py:   self.name = "x"
来源：http://dali.c1oappe.top/Article/details/gteztlscyw.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtqzevoxet.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtqqoofzqz.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gtnhzejqir.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtiveshduw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shuidangran.top/Article/details/gtxoelvaac.html

Ruby: @name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtdlclmbci.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtpiaokcij.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gtxhflbfkz.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtumofcvji.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtdkspamlb.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gthflogvtu.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtnfhipizu.html

Java: String greet() { return name; }
来源：http://dali.meibo888.top/Article/details/gtkwppwqoc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gttzucixin.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtntcjmebw.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtfuuyzkbo.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufnmhnzw.html


<!-- 参考信息 -->