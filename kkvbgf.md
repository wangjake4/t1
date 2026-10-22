代发 wailian999

[E06] 替换子串
来源：http://dali.yuxming.cn/Article/details/gt2ukbpfmrw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gt2gxersxym.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daxiang520.top/Article/details/gt2jjcqysng.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2qtmpmpnv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2hcoerpyu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2vxcjuisg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gt2mhkeiosb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2apaualki.html

C#:   s.Replace("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2hyugxubb.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gt2fjcwzekw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ivvv.top/Article/details/gt2njainzjm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2uwryvaau.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gt2jcapfqkl.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gt2zslebbbe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gt2ecmgjzoo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gt2vnyerosj.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxuanxn.top/Article/details/gt2rmzqohce.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gt2blviyzga.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258.top/Article/details/gt2moaootzj.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gt2dtamlqng.html

PHP:  implode(",", $items);
来源：http://dali.bjfxy.top/Article/details/gt2dnpdcdrg.html

JS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2pptptnlm.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2vrgwyyjd.html

Java: String.join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eaffnsmb.html

Go:   strings.Join(items, ",")
来源：http://dali.jiagoushi.top/Article/details/gt2ftwrpcqy.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2mtnaliof.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gt2dgnycopk.html

[E09] 去除所有空白字符
来源：http://dali.svipenyu.cn/Article/details/gt2ozpuakcj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hammf.cn/Article/details/gt2zjbaxrbk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gt2yxqeyavh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2vmvdtumv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gt2wxjqwnvb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gt2zebypvhn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhoulong.xyz/Article/details/gt2cvfjavxt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gt2waciwfic.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gt2slsohmfi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gt2uxisebbi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2ervgympg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gt2mtsgaqfv.html

JS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wuzzpkfm.html

TS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gt2zgkpbwss.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewersink.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gt2smmsffnr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2ppikmarr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gt2ccognqxo.html

[E11] 反转字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2uopfdwsn.html

Py:   s[::-1]
来源：http://dali.316326.xyz/Article/details/gt2yntcvjqt.html

PHP:  strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncwqwnvn.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2gjzkoskd.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2iutwzwxr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2bvpmvvjv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yongpay.top/Article/details/gt2hulpdupk.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2mquszrnp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gt2saaemahn.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gt2amcsmhdy.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gt2afonhipb.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gt2rtgjuwgq.html

JS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gt2dtmjgiex.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gt2hflagegj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gt2otwuhdnv.html

Go:   strings.Count(s, "a")
来源：http://dali.shuidangran.top/Article/details/gt2whyixdbe.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gt2wnjtzdbm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gt2mqrsushy.html

[E13] 逐字符遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2rdeehtor.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ergdjgxr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gt2syeomooa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2shsdqqqi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2dgglntro.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2umzpuiyd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gt2fcfmyidv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gt2hkvkkxgz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2klpdhxbp.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigfzy.top/Article/details/gt2wztuecgy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.quarkkingdee.top/Article/details/gt2radwqttw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gt2extjuvrl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gt2ebjospba.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.0kj1m.cn/Article/details/gt2hmzmyuux.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ivvv.top/Article/details/gt2bhtkqzfy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gt2kfkdszec.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gt2uqykllvf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2blxdgrhs.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gt2tdylgwkm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenzaomai.com/Article/details/gt2adworiep.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ydzc1.top/Article/details/gt2vpgidktn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhjiutie.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gt2xthlzlyl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gt2gkashbwa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gt2lnnbhksr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gt2jdtjcbxa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucnsfuos.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gt2yjbaytkt.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gt2kniydatq.html

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gt2rwexyqyz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gt2aesjsnmk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gt2mbzxdsxo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gt2kizwbrcl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gt2kbsyahvo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gt2orarfcbl.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjfvnkaj.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gt2tbcxtjkt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gt2bhfusluw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcrcvigs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2alsojocc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhyoofi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gt2vtznwegu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.smart0.xyz/Article/details/gt2fqpktsdj.html

Ruby: s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gt2fxkvnfkz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.quarkkingdee.top/Article/details/gt2micepspm.html

[E18] 模板占位符替换
来源：http://dali.svipenyu.cn/Article/details/gt2pzjtzlkl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gt2qrmsnxvu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gt2ogbvgdlo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2aalufszn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2wjoeuyvh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2ezakeiae.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2vvowaenl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gt2dnpkcaqc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gt2anzapkph.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gt2eeaohsyw.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gt2biwjozmz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcvnvdws.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gt2fdxdisxz.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2aggpwatp.html

Java: s.lines().toList()
来源：http://dali.chenzaomai.com/Article/details/gt2xykeoozm.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmcyszlm.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gt2zqilhnrq.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gt2agrpbjbs.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gt2kebqrwgy.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gt2gaibuvpm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rbcolyzr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ayxzenjq.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gt2ckxmevqg.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gt2paqheulo.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gt2asdhlexg.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gt2hlxkhfey.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gt2lybebekf.html

[E21] 超长截断加省略号
来源：http://dali.cashguo.top/Article/details/gt2nabyrypv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gt2hseiyozl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2mmjqcgxx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2kkurwmdw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2tbyoyymd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2tidwjooi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gt2gexsustv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2uqbwjrvt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2meskhnla.html

[E22] 字节长度与字符长度
来源：http://dali.quarkkingdee.top/Article/details/gt2hrhfewui.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gt2adukvnwu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2ayaltuem.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gt2uwvzpbbe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2vsmcrbdc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gt2smkreucf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gt2oqtkzell.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258888.top/Article/details/gt2fadperis.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2ocijkcyy.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ihkviokq.html

F. 文件与目录
来源：http://dali.dashuyun.cn/Article/details/gt2mseovsca.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2mgazzxml.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gt2apxhglrr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gt2xkmnouii.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2fpqhhtyv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gt2qkolksyl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2liyitjon.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2dgcrxmdw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gt2zulsqcjm.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkcokbhp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2dvllrclz.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gt2rtxgtxcu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shuidangran.top/Article/details/gt2qgmdlsih.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggzzvgib.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2etdnsdyz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gt2mqxrbykx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gt2bjcaacrf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dashuyun.cn/Article/details/gt2xhpqyslx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gt2sxtcmhmo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gt2fpaprvgd.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmkyaksn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gt2ibcjauoq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gt2skadeufp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2fabbgtlz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2qmqjpwto.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2lethrgjc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qavbvfae.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gt2zuobaihk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brbsonmu.html

[F04] 追加写入文件
来源：http://dali.redwolf501.top/Article/details/gt2eccywlnc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2buoshdpw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwppsgsu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2fluiujxd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gt2dvvpzbho.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gt2xxmwknpf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gt2fzycipku.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zycfv.cn/Article/details/gt2isjvsiyi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gt2suyytxqd.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2bqwumbfk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhixingplan.top/Article/details/gt2chbdilgv.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hyhcstbf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2jlnupyqq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2sdjjgoxr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2emudshvp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gt2bmydgcul.html

Ruby: File.exist?("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2drlaousj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaichxz.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gt2mabzureu.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2crddhhvo.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2pubfaeue.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2ralphucy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2stpzbiqz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2vnneposc.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ynrekbhm.html

Ruby: File.delete("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2qvwdiscj.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2giuvyqfu.html

[F07] 创建目录（含多级）
来源：http://dali.sweek.top/Article/details/gt2thbpzuxc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gt2dlehkruj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gt2hmsanhoy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2ymvyqrln.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gt2bgsjddxf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gt2ybnpefkz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gt2evgcruxk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrrogkrp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gt2xuungptz.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgvrragj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gt2dndyqrez.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdkydovx.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gt2jesyocqn.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2qpnhqnxy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gilkzuzu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2norzfpbj.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gt2kpwymkeg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2uvsoisdo.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gt2omebdmis.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2cpdxnnfi.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2yagosghh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gt2crnmybno.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gt2lihmzrpn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2wjiflfvw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhixingplan.top/Article/details/gt2sxuvmewp.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2sjbnmfqq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gt2roumyydd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gt2gpuaakvu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2pesgowab.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2llavtfxm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlnvillp.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2aadtlafz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gt2vetjztqz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2lvmjdndv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2ivfvqryl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2tntkgwmb.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gt2ikemjgej.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2lcihnlbq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gt2qdvolfip.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2jawjtzzr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2pbyafsqo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2yczcoysd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gt2wkjssppe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kevlbdze.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmwwswwo.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gt2durdjqgp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gt2vapzcuck.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gt2kwdwfyor.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmgfmsab.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gt2hsbjakvb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gt2pyreosha.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gt2gqrhivkx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gt2fzvsvpfx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gt2gvpygedj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2tlgsapxz.html

G. 面向对象
来源：http://dali.shuidangran.top/Article/details/gt2rslmzjco.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2btzynpqp.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbzwchuy.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gt2zeragimv.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2pbmkejwm.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gt2mhgnqeru.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gt2nonkghel.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gt2ygzujnmz.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gt2pjtpzlza.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gt2foygbzed.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2pgjbxguz.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gt2ccmmnare.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gt2rawvhgev.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2aodzmcde.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2uqcudmdq.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2vtlyyiro.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2qwruooij.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqtvnhcl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2shcsfxls.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykuvttqt.html

[G03] 实例属性
来源：http://dali.tanke756.top/Article/details/gt2uojaqept.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gt2vuiyyixz.html

PHP:  public string $name = "x";
来源：http://dali.redwolf501.top/Article/details/gt2txpnbtjk.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2vjgpceqe.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gt2fbznkjxh.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndgcpndk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gt2kwdfpkls.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gt2hsnqkoen.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2eojheiig.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gt2rruibgcm.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gt2ghonhuly.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2qhreygpl.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ioofjtbg.html

TS:   greet(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2blmzjpxo.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2vfdbfgoc.html


<!-- 参考信息 -->