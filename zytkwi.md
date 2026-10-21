代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.tian-w.cn/Article/details/gtwgqynlfz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aibaodan.cn/Article/details/gtirhiskbp.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gtieejzpjp.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gtzopivuag.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gtajfximql.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtityusqkf.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtstssunij.html

Java: String.join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtzwnzhdsp.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gtqdcpmvro.html

Ruby: items.join(",")
来源：http://dali.yongpay.top/Article/details/gtarsvjfmo.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gtaqxjvfgp.html

[E09] 去除所有空白字符
来源：http://dali.haohaochexian.top/Article/details/gtskaujnzv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gtlwsmxyku.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtszkklpmp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gthsrtnfum.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtylfvslgs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtrnhulcuk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cdnleiting.top/Article/details/gtmgzvhfjr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtgucerepv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tanke756.top/Article/details/gtwinavqrm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.quarkkingdee.top/Article/details/gtgdfbrvzk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtybpwqyry.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ehwqpu.com/Article/details/gtifvuyeov.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtcbfsxhuu.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtengsuzdy.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtcpufvfoj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtjyaltwjv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtwszbkoyk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gtozmvbked.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gtbxuwvhem.html

Py:   s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtnfzcxtyq.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gtnckncstx.html

JS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtgtbsjhot.html

TS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtvfyjrdzo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangdashe.top/Article/details/gtdpjlxyon.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gthrdoircf.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwifpkle.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtopqgochu.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gthrnnmdlw.html

Py:   s.count("a")
来源：http://dali.ivvv.top/Article/details/gtiglcgmat.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gtiujzyjia.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtiocfkins.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtocenxwfr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgufenzy.top/Article/details/gtxkgtvzxy.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gtxeaufkob.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gttdqnkfnf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrymnyrhi.html

[E13] 逐字符遍历
来源：http://dali.birdmap.top/Article/details/gtqyqtqvtv.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gtkjdexokw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlrybysyx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoryhqrdk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtixqbceil.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtfhsjutam.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gttozhzccz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gtjdkkmyjq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gtgfxzvxdx.html

[E14] URL 编码与 Base64
来源：http://dali.hongshengwenyu.top/Article/details/gtkhopniqh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gtsizasdun.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gtsprdjbbz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guowangkeji.top/Article/details/gtczchxamr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gtsjbulrbz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guannengcc.top/Article/details/gtrgjitqub.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gtrburjpmk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gtzighgosg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtjlnclqjg.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gtpdconkgd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtotiemxsp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gtxnszpkts.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtekquibyy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jiagoushi.top/Article/details/gtecsnfgnp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.9152youxi.cn/Article/details/gtetkdzzen.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gtfzifbguy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fzhhl.top/Article/details/gtywonarup.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtynbssuwg.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gtvfdfwoft.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gtihitwpsx.html

PHP:  number_format(1234567);
来源：http://dali.cqqwz.cn/Article/details/gtyanknrwa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtzxixdkre.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtvgcbkzax.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuxming.cn/Article/details/gtfesfgtni.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gtsyxxirll.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtxxjxsovo.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gtipvujcux.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gtexvxomil.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gtotqpkysz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gtqtwwvjtn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gtvaigpalp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtlcmesnom.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jyoumei.cn/Article/details/gtebqqwiey.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnqzz.top/Article/details/gthifuydsn.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gttswxroxx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmdsvndl.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gtwvcxpjup.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgfzy.top/Article/details/gtvaiodtyy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gtwoyumaqk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtomojorzp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtubmurnvl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtqdwepsii.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtlocapnff.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gtdppqiwbk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gtxsmbyzeg.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gtafysphvk.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtwnjotolj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtqbxubnzx.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtoilabsdv.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gtgvtnlmmk.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtupmyakbj.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gtitqsoiwt.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gtoajygopd.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gtesblyyxp.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gtfsojbpgh.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gttmshttcj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zdqjudy.top/Article/details/gtofkgadqb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gthsimmyny.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gtxclryfya.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrfvfkpj.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gtwetuundn.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gtfkcnkobi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gtkcdhamln.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gtuothxwyy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gtlobdtndp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtatutoyau.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtmjllktij.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtpzhxrrjz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtvjvmkqcw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtekabodgy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gttehhvwrt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtfxuqruqr.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gtiwiuokqi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxuanxn.top/Article/details/gthfunmzgw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtmxjsnduc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtktaqbjew.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtdglhwjek.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gtzjtscgcv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gtpqwkwuvv.html

Ruby: s.bytesize;  s.length
来源：http://dali.fengsongda.top/Article/details/gtuigggnuv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtpewfufkp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtojofdlsw.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjndvgusd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtzaocsrba.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gtdjndhqna.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shzxlz.cn/Article/details/gthkvcqvhm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gttexwscdi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtuxikkmah.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtilpelqeo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtyueaxdyn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gtgnyhxylr.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtbsgnvmon.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtoeixlgqf.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gtqonjndri.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gtjgwwdibb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gtzhmxbxtg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbesezryg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtcovtznrs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtqddzwtib.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gtjbacjnir.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gtzecbhojx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtobmmcsqj.html

[F03] 写入文件（覆盖）
来源：http://dali.guowangkeji.top/Article/details/gtowwnootv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtuzfcfjwa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtckmhavka.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtqehkcisk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtjiqoayhf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtojcxzsyf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtfglfpcln.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gtpgwlhehh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtytjoruzf.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gtvipgerpc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gtepvhhbtv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gtgmbouore.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gthlpmplkl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtnkhtpnal.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gtakzgaenj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gtqxavymta.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gtummtolmf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gthawwzdgd.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtyfneefgt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gtctegvopa.html

PHP:  file_exists("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtriaqeazr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtavuaeuxy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtfaqcytwp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtcnbgcxwv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gtpemlvviu.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gtfatdsrwk.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtcbaluspe.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gtvodzrrnr.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtnswjvekr.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtplcmhfom.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtgbuhfhht.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gterqpyhye.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtuuojyyhe.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gthdarklnk.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtgaukxupn.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtkqxkpzdr.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gteinqswut.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gtwdnowjbn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gtslotagpj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtunowyfuc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtmtqbxfyq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gttnhtvkwv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gtfotoyydt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jlsjyb.cn/Article/details/gtqkrwrvln.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pengpengdd.cyou/Article/details/gtjfrbunba.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gttzdxorqu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gtnudzqkmy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gtcmdsowja.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtlixqxlya.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtonbodrdu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtzeownbxm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxuanxn.top/Article/details/gthsrzqpeq.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtrbfnpeqa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dashuyun.cn/Article/details/gtdpugzrsq.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspvkzohc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gtrbaxqhua.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtgiusyhfe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtrtpcjtsg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtqvppefdo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtpgtfmlys.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gttusslngb.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtwikbfkmw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gtlwrpqqci.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gtorckajii.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtffxknsme.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfnaaczc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtduxwgnse.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gttaahgklf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gtyrbplftk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqphsqcqc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtsfbitybq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtciczrmkm.html

[F11] 复制与移动文件
来源：http://dali.yangfankeji.com/Article/details/gtjentqyyj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtazusapyh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtfswkrppb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtzkxowsxm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtwxvebomq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtjpafrotz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gtjwryxnsy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtackggrsj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gtocqmzpfi.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gttkiryvmk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruwoeflg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gtfaiogzbq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtvkjndnrw.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtnmnaxwpz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gtmqmfptpn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtgslbdsbe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gthavzrccm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gtutpfyadg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmfapasfl.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gtcuqorrdx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvpcorhbv.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gtewudipnc.html

Py:   class User: pass
来源：http://dali.birdmap.top/Article/details/gtqchabtca.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gtfugfdgkf.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtmpgkkwxs.html

TS:   class User { name: string = ""; }
来源：http://dali.shangyingyoupin.top/Article/details/gtymwguuzb.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gttmxsxzbi.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gtvcprpiqa.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gtmpiourlo.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtkimtwmei.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gtykpiphdu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gtdvticytl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gtthcvbfxs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtohodbdly.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gtepzalupj.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbweawdsg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenlongwang.top/Article/details/gtuvupdsjj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gthtkfhrui.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtumgmjkju.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gthaaskhfu.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtnjndoayj.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtltvvwsgg.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gtcgkaohcy.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtzdwmuyhy.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gtxzzjdovk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gtbikgjhpw.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gtfrccldwp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtggpxreyf.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gtbznficwo.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gthxkcvrqx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsznxtdqy.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtaqmmqoxq.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtsqueaanj.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtzkjtfsww.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtehketymm.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtqprlqfpz.html

C#:   public string Greet() => Name;
来源：http://dali.xylfe.cn/Article/details/gtdhcfskdv.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gtyxhqodla.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gtkuncoqfs.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtxwqtbnlz.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtzczfgwer.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gthhzduqsl.html

Java: class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtzjsihomd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gtdvcantzu.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gtediamabh.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gtywgppmpf.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtahfnbeeo.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gtvfbasdpy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrurmljdh.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtairzgxjj.html


<!-- 参考信息 -->