代发 wailian999

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfsigcoa.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gttfoefwnw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtugcnhqhy.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtjyvcakqk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yongpay.top/Article/details/gtpljkljap.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxinkj.top/Article/details/gteacjexnf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtxkjruera.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtjazacjde.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gzhubu.top/Article/details/gtntmcpjma.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gtdqwxljou.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.smart0.xyz/Article/details/gtjghvqyxq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtethacvkd.html

[E02] 重复字符串
来源：http://dali.zhongyouzk.top/Article/details/gtiwavxzeu.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtkjbbvnvg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.andypj.xyz/Article/details/gthhnthrsc.html

JS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtnwfnhxea.html

TS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtjeablftx.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtwuieutnt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gzhubu.top/Article/details/gthqbpgstu.html

Ruby: "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtponayxre.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gtlcljgsfk.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtadieqprg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gtyphiezgh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtftzsbnlq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtyrhqgmwc.html

TS:   s.slice(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtwbzcsbkc.html

Java: s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gtxzhymnyh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gtiffiizzx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugdlwutn.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gtvxwnzfga.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gtsczzkozq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtgrrvuvvw.html

PHP:  strpos($s, "x");
来源：http://dali.sxryk.cn/Article/details/gtilcudhii.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gtrzdyoyih.html

TS:   s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtcragerth.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtwcylapiy.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gtvbnpsnfe.html

Ruby: s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtuogzctzy.html

C#:   s.IndexOf("x")
来源：http://dali.daria6918.cn/Article/details/gttvrhvbad.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhoulong.xyz/Article/details/gtmkadvelm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xziqi.cn/Article/details/gttlvfapia.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtfboemapv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtkakwhynx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gtgteyhvyn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtndhhlixc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zycfv.cn/Article/details/gtzokifgct.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangdashe.top/Article/details/gtpxzfhpbf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtgeyewrcp.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gtgrnurotd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtkykmhpjv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yongpay.top/Article/details/gtpobeyltr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtqsznrjtm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtglqhhktc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtjmgiectj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtipgwkwer.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtniyhiiwc.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtjailribu.html

[E07] 按分隔符拆分
来源：http://dali.yonumen.top/Article/details/gtpirplrkd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jlsjyb.cn/Article/details/gtjfyghyhj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtxifadejb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ydzc1.top/Article/details/gtzlvkollf.html

TS:   s.split(",")
来源：http://dali.sweek.top/Article/details/gtzqdnvdju.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gtveunbzqi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gtygnqugwf.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gtrtofejrb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.316326.xyz/Article/details/gtjyiwcdkd.html

[E08] 数组按分隔符合并
来源：http://dali.aibaodan.cn/Article/details/gtfittdhfh.html

Py:   ",".join(items)
来源：http://dali.jqgufenzy.top/Article/details/gtxjfjjlxb.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gthwbqdrvz.html

JS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtuoeborpj.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gttfchjbih.html

Java: String.join(",", items)
来源：http://dali.xuanzx.com/Article/details/gtejthrgxv.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gtoicdxouf.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtnihjcont.html

C#:   string.Join(",", items)
来源：http://dali.nwbrower.top/Article/details/gtlgqmqtgv.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gtrfvtuflh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gtckwtcoeh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gtyyyyhkvd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtwechyooo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtmornciem.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtxccqtocs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gtkyehirdi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gtjpwuhsij.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtxpldnwgl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hywenlv.cn/Article/details/gtyhrjcuft.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtazxqtwkn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yangfankeji.com/Article/details/gtuckeelhs.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtwhaqcmtu.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtqamcntif.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtjptleuea.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtoujsgcdx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtpbnntizy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gtgttctwso.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gtdwiyrvjs.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtiwizsnep.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtmpftswft.html

JS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtzmjturvf.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtzrbrhfta.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ehwqpu.com/Article/details/gtwmnlllvl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gtytljqxra.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gtrvavrxto.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtzehtmayj.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gtpuxjywvm.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtkyhwuznc.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtqcocheqj.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gtohyzxcid.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtzalgiwjj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gttyqasjyn.html

Go:   strings.Count(s, "a")
来源：http://dali.yuanzhike.top/Article/details/gtypwpnsve.html

Ruby: s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtdsvorcdo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpvlkqjv.html

[E13] 逐字符遍历
来源：http://dali.nanxinkj.top/Article/details/gtgjsnxmqp.html

Py:   for ch in s: print(ch)
来源：http://dali.yonumen.top/Article/details/gtfsknbqpb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gtucmavkot.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtmkmuqevr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtxngphyhr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gtxmvawqnj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gtzfymvowx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.mhx1999.top/Article/details/gtrjuvothv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdmhtmpl.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gtmmkstldl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtsoxvxrdf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.iojbl.cn/Article/details/gttnkthzva.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gtsasibivl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmrwoqiz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtdsrudjbp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gtylgikhsv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gtqkvbuqfa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtciryoxpv.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtaphucode.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gtizmusdkr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtgwiokfpy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gtbbcobygp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gtfyrzknua.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtvusrxsvb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtgoshyqar.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gtsrdwalzm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.9152youxi.cn/Article/details/gtoiraklbk.html

[E16] 数字千分位
来源：http://dali.bjfxy.top/Article/details/gtkygasijc.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gtcasnnttv.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjcqeutq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtgrwrnxay.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtuszjuotg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtoxbqeadj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gtmskbgtdv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gtziiwhyvb.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gtchesmevl.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gtwzsmkyrx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigfzy.top/Article/details/gteawxpuqo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gticzxfukg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtqklrxiuq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtvbboqkeu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtivgbqixz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtnlhzwfts.html

Ruby: s.capitalize
来源：http://dali.cucudq.cn/Article/details/gtwgzialpc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gtnqleorqs.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gtruiqqgoy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.mhx1999.top/Article/details/gtiznbrdgd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gtbhfiawtd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtafytbtmu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtaualzjrw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtcpivdshs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtcmpeklpl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gtffjtxddc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlixueieo.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtcbmdpzgx.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtyflyuptv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtrfmrrknh.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtvfdiosqb.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtebzanskv.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gtafribnjr.html

Go:   strings.Split(s, "\n")
来源：http://dali.dianchejie.cn/Article/details/gtegyznuao.html

Ruby: s.lines
来源：http://dali.yongpay.top/Article/details/gtxtvfooua.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gttwtfnskj.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gtkvtywpjk.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gtwhtithem.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.snrcjt.cn/Article/details/gtxjjbweme.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqfwnxclz.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gtqmyuyomq.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtorhehfsi.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gthafrbbad.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gthqclflrf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.meibo888.top/Article/details/gtubyyklov.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gtzcvutkqu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gtnbxptgrd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtcosjieqe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtnaptxwgc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzaaxpld.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gteuetminh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrmvhokl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtfprdumwn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtxjjpswsm.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gtjdhuohbd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yanxiufei.cn/Article/details/gtcnmnzjcf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtrlyqvzbd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtplleckvj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtitgnuaon.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daria6918.cn/Article/details/gtbvpvrzgu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gtjaqcwuae.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtsplvdghl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gtmhrfznja.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqbdwodx.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtbwycundl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtefopvmxo.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtdivrkjdi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gtckboqwfl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtgnttngts.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yonumen.top/Article/details/gtapvuxzlv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtzcwigtsy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtsjzluauo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtrxxkspqt.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gteaxyfxrq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtnerpggoj.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gtswhmriyk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gtraghwggi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gtltpefnol.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gthydgpdxd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gthuhpxful.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtcvmbxfnw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gtgtmdglho.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yvedp.cn/Article/details/gtxhzpdhtw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdbzubpe.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gthvxfvplo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gtfdcehfoz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtjlterads.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtilnyalkx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtydyyuxnx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gtrghqcfxg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.snrcjt.cn/Article/details/gtecpfubjo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gtfbxhkvyo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtsorcjluw.html

[F04] 追加写入文件
来源：http://dali.gaohongyu789.top/Article/details/gtxwpbfdlp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtgkduwffp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gthtlkfnhh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwbvblrc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtmmkuqnlz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gtlzxlpibm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gtbutsfntq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gtisksbxzm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gtpjstwfap.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtihykpukw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtzotpijnx.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtnetfmexm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtnwargfor.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtuemzevue.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtmtqpqgrh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gtrbmztnsl.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gthibmfrnf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtphepwhlt.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gthsyekeuo.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtlgpagvsf.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtegbqoblf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtznvrunvn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtmowpvxhc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtzhglygez.html

Go:   os.Remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtbdlwyjzb.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gtyyjosxrc.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtkbvhxjbb.html

[F07] 创建目录（含多级）
来源：http://dali.jqgufenzy.top/Article/details/gtttldixbc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtbidjrvfh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dianchejie.cn/Article/details/gtlewramqp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtnbuqpngd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmcgjhtp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gtncqyloed.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gtsgsbahxs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yonumen.top/Article/details/gtoweitwgq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gtehncttqs.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gtcploxcyu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gtacnbyoqb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gtakynooor.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtsztfaxom.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtepgtyjjl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtiehzunfb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhixingplan.top/Article/details/gtbpeesakp.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgptlvwi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gtdhcveiro.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gtxcefrvme.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtiosjxnve.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtsjpaffmu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtywzpirgg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtitrdkqwr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtiohzwlrs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gtcpaahkcy.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gttigopfom.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtrbgqbnus.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwrwhdlm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtqhpshxhi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtaztopjyv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtuopxwmeo.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gtuuxxgrxx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gtihfhrbuu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtqdgouwlo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtwskylhrx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtxklvojlb.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtqyyuvhgb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtsrkjtidr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtecctihtt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtijevmjms.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtdeonheto.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gtwzuwexgy.html


<!-- 参考信息 -->