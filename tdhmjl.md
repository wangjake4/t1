代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrjkegiy.html

JS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnfznsqg.html

TS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gt2mggysjru.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gt2vgoekzcl.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxinkj.top/Article/details/gt2tiaodovz.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rklrtgpy.html

C#:   string.Join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gt2umixprwz.html

[E09] 去除所有空白字符
来源：http://dali.gzhubu.top/Article/details/gt2wdfhjukf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gt2qunyaaph.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nozcaahp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gt2yfpwshjq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gt2xmxgaxhs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gt2gixprvmb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cdnleiting.top/Article/details/gt2csmxxioa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gt2owrepgyv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2jjtqvysr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gt2kueovlcc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ygyhpejr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258888.top/Article/details/gt2zdhgabac.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2ylexsyas.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xewyborr.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2dtxoomfm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2tujclsfw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2sixcswda.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenzaomai.com/Article/details/gt2xlkqdcjn.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gt2elicypur.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gt2spvxcrao.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2dpaqebqe.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2olqsenpn.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2xyugeujy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2vmdkefbq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gt2rspiwyno.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gt2zutwkqss.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gt2irbbqqsx.html

[E12] 统计某字符出现次数
来源：http://dali.ivvv.top/Article/details/gt2ayydgdtd.html

Py:   s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2hfqvpobn.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gt2docjyblb.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gt2zevvifjh.html

TS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcevampz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gt2rteoozyq.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gt2qkrgsbhf.html

Ruby: s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gt2buycukwr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gt2nyherhod.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gt2nlnovmew.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gt2fmwpmcyx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gt2mygljkbt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gt2djdsvyrc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2royyyylx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2dhcypdfe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gt2oujbodsn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jianghu66.top/Article/details/gt2kbhnpljc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsmlulql.html

[E14] URL 编码与 Base64
来源：http://dali.vqdsnc.cn/Article/details/gt2jrijpfrb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.andypj.xyz/Article/details/gt2xnfrbhpm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsrgdsdw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2txsisyxl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2byowxkvw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gt2farfipzy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gt2sndeugta.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gt2tovxlesg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2rpmdvmbw.html

[E15] HTML 转义 / 反转义
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkxoumcr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gt2fkrgcvtu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2raaarvao.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2eapcnxzy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gt2djqxamfw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.svipenyu.cn/Article/details/gt2lmuhpfov.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjtelnzx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.0kj1m.cn/Article/details/gt2fpubjcrp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gt2cjznnarj.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gt2tcyimqvp.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gt2nnsqyioj.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oijlmzrz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gt2shmifsdy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfqitao.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqzwdsmd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gt2ceqwfbay.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.meibo888.top/Article/details/gt2rzrxdvzh.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigufen.top/Article/details/gt2wpiatoog.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gt2wnztnvgw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gt2vithzneh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gt2hootuxil.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gt2thzkyvrb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gt2wavbrbkg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gt2tpdhkrrs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gt2wdpfehpt.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gt2pfbukbdw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fghktyaj.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxkjsbah.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gt2lktkumwe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gt2wnxgsnur.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2rhqbfoyc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2vvobespx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfdzoicw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2aatrjwcs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gt2nystaapn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gt2bhwslxzx.html

[E19] 多行文本按行拆分
来源：http://dali.redwolf501.top/Article/details/gt2tjgeubxr.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gt2nltgkcfs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2vjpzcspb.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gt2mpxgktos.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2odvdjess.html

Java: s.lines().toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2kyshjqlq.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofrunday.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gt2fdvbaymq.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gt2onqeyuap.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gt2isrwvwsk.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gt2zbwozoyh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gt2dyxwzanl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fengsongda.top/Article/details/gt2uwdlccvu.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2fgwgyvei.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytqwbhwj.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gt2nuezjwos.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gt2eudqcgwg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gt2ycqpfyqy.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gt2lcdkcczc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gt2qjijmhbh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.meibo888.top/Article/details/gt2qxtypwqf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2ooqtinbk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2mynluuhi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2ukcvofgu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ppjwa.cn/Article/details/gt2wexelfgd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2mwxogfpw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2pdcketym.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gt2ewstubwg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gimxtpir.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2sblfzaxw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gt2mplzjbcn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2dsabpbcv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rweudxcu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gt2keuszatf.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gt2zzjcinki.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gt2mpxyoivo.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2mzygpean.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gt2sphcoswy.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2fgjutysf.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gt2eohcudot.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgfzy.top/Article/details/gt2nrugfitx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdvopola.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aizwys.cn/Article/details/gt2vbwvqevk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xyxlqdpx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2pimzcytt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hywenlv.cn/Article/details/gt2kcewjpkr.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2ivnujysa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2nsbdtfjw.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gt2llsncrnq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gt2uqfqxcyg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gt2tgcmdkvm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gt2fcowwcet.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttlvpkaz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2tzvcttyo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gt2xargzygn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jdkuqsck.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gt2qhfikale.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gt2ybaudjtk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vuvxonwv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gt2dxvkcpts.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2mghxtzic.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gt2ekjoyokv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fzhhl.top/Article/details/gt2mgiqevbv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dmhukbeg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gogol.net.cn/Article/details/gt2nvjwvacj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gt2chhorugd.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyntijus.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2ciwwobfy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gt2jpkjxxxa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2ydhuqhmh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2oyhzcspd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gt2mkjfuwvz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gt2evtvhidw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lowqzieb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gt2yiwscnwd.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gt2hkqujthf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gt2ogadliez.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2zyxvmafk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjrqywrn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2yajriyjq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2cdxpjvsc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.bjfxy.top/Article/details/gt2wddvvqql.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2uesfoyxl.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvtufovp.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gt2etddckmo.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2xkbscnhd.html

PHP:  unlink("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2rnqpchcj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2msbvhmmh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jatnemkp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2rhifhneb.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2mqwusoyq.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2jxhbzuto.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2xovpkjaq.html

[F07] 创建目录（含多级）
来源：http://dali.tanke756.top/Article/details/gt2lsegyvre.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2olpelpuq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gt2ekzmjfec.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gt2qhtinwvo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gt2aroibhat.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gt2difwhtfj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gt2oixrazjf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gt2xnryfnpl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ybcxt.top/Article/details/gt2fphzytag.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gt2poigskue.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gt2zehzyrwx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bsstrort.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2mdklfcep.html

TS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gt2oxuoqjxc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gt2upvlrycj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gt2nnyzdzbr.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gt2qsgqjqsw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2eqbfoead.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gt2fqfkanrf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2gjqoarcr.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ysxlnaht.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gt2tadmoobe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gt2rmelnmjj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2hyvuldcf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gt2auagxnsi.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2xvpzfdxs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwtlahqt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gt2dmkbdzac.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2zvcctldz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gt2jhclpuiv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2zdpxemhp.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2wyrxwwfp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gt2rsyeihcu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2hagdokht.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2ytjfxzfe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ynzbuzoo.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gt2aaitggjo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2kyctyxrl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sxryk.cn/Article/details/gt2isgadzur.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2guwezbzb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ibponbdc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2rjzilgjr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gt2lvnqstkh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2ptuvbtwh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gt2ghukrwpm.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gt2hbhuzcjp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gt2ccneddot.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gt2ueqjopfo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gt2oqwukmcj.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gt2yjxqvoux.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gt2zqzruagu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gt2zirhwbbr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gt2brnobkyr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gt2aggayxal.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2nwxfsrmk.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gt2zhbmdtpt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ycbocixg.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gt2ngalxuui.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gt2atrwyuhu.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gt2poybygzn.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gt2ybzhrhqt.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gt2lkqygstp.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2mifexdqb.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gt2setixsav.html

Ruby: class User; end
来源：http://dali.haohaochexian.top/Article/details/gt2xwilciuf.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2nnazivxx.html

[G02] 构造函数
来源：http://dali.hfpthk.cn/Article/details/gt2drsczdpp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gt2dpivbuob.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.svipenyu.cn/Article/details/gt2jamzcewx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2mhpoblsp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btxxokfc.html

Java: User(String name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2tkarwumb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gt2meyfyhdj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gt2mjtvxqwm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2homtfbnv.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gt2pwiecfuw.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdupuorz.html

PHP:  public string $name = "x";
来源：http://dali.redwolf501.top/Article/details/gt2vpyodnws.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2xemzyzyq.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gt2xdxnbvxz.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gt2urwhdbnr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gt2aowvvxvs.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdskaszq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ydzc1.top/Article/details/gt2cdvbycfo.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gt2usgyuoay.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2ydsoxmts.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2wleipuse.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2lirdkyww.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2hxwgopdo.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2obrcvvns.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2zvtzoaxb.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2hrncmctj.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2jivxurcj.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gt2nyrhluho.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gt2fgrpblgq.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2bpbthgbq.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2citagtcl.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2albsrqix.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2mxputxil.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gt2gtzrpjat.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gt2givkddlc.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gt2ewkeglhm.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjuseeuw.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gt2yqsapefj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2cbwgucna.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2mkqkwvpr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2zfaonpif.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2rmoertyr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gt2hckpwows.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gt2vlxyhqcp.html


<!-- 参考信息 -->