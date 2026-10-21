代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gtclqtzpaq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gtjgjgtmkw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cheryme.top/Article/details/gtigmxytzm.html

[D26] 数组转字符串
来源：http://dali.xinyue.icu/Article/details/gtzlktwnqc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gtodfxqwte.html

PHP:  implode(", ", $arr);
来源：http://dali.daria6918.cn/Article/details/gtghaavywt.html

JS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtncaozrsn.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtwkbcmzbi.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtfmnldppb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gttiqqehcx.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtbqbzikyd.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtxiwtzyxe.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtiobkxayz.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gtxrmlgdin.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtzntywckl.html

[E01] 拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtuqvazjhv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcufmykx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hfpthk.cn/Article/details/gtjnytesmc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtjytvvygw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtvqbpdkyd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gtqiapgwuy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtineohqsh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hammf.cn/Article/details/gtrdtwqmxs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtbrqusxri.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gtzsrcofat.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvjwhtrb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jyoumei.cn/Article/details/gtblwdegey.html

JS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtwmidjfzf.html

TS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtzptvfbzg.html

Java: "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtsoumbqkg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hongshengwenyu.top/Article/details/gttpgnbbcd.html

Ruby: "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gtqalkarqn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.bjfxy.top/Article/details/gtwuulxsvr.html

[E03] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyofnutsq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gaohongyu789.top/Article/details/gtwnppvxig.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gticzpwkmr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtafimvpsp.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtjqwbllpv.html

Java: s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtqfizcrir.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtgswyqltb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gtiiflqcbt.html

C#:   s.Substring(1, 3)
来源：http://dali.tanke756.top/Article/details/gtwckauchy.html

[E04] 查找子串位置
来源：http://dali.yuxming.cn/Article/details/gtjrrxbbug.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnyilvye.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gtuzxwioec.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hfpthk.cn/Article/details/gthlgnrlns.html

TS:   s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtlbfnircp.html

Java: s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtlhwmupbc.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gtbnczxtqq.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtlqsxmtrt.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtvgtlgomv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gtyeqdnplf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtzwjrshwt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gtzpgweubd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtnwwxqyqi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkxifidd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gttxvdzerz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhengqikj.top/Article/details/gtlzwhiaxk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gtdxsjkelb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtrcqnnpmt.html

[E06] 替换子串
来源：http://dali.vqdsnc.cn/Article/details/gtfsctayva.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtzggetpvv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yongpay.top/Article/details/gtvdhozzef.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtpokmwhks.html

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtozfdncmk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaewpsiaz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gtdisqtoaw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtbxfzshsz.html

C#:   s.Replace("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtpziykgmf.html

[E07] 按分隔符拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtserkyfir.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shzxlz.cn/Article/details/gtezbhsspw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtpmoswzrp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.mhx1999.top/Article/details/gtsjafpdmc.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gtqnxmfovw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gteacgvfme.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gtoypwaekt.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gtrhrsbaca.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gteomrqquy.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gttjeluuax.html

Py:   ",".join(items)
来源：http://dali.yuxming.cn/Article/details/gtkofhkueq.html

PHP:  implode(",", $items);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzhzeyjk.html

JS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtvhkmimys.html

TS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtcgmdrjhm.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtujiqolyl.html

Go:   strings.Join(items, ",")
来源：http://dali.tianlin.xyz/Article/details/gtkkdjjksz.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gthvjgxpcd.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtxrqcvfhm.html

[E09] 去除所有空白字符
来源：http://dali.hnxiangtu.top/Article/details/gtjlwvccag.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gtipkhpvqp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtsjgrtlxo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gtihgvamkz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtwahfwpgu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gtsdrvduqg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtflaxebkm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tian-w.cn/Article/details/gtzfdzmjxd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtiluskstm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gtwuzgsmnq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvepomnxg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fzhhl.top/Article/details/gtvimjvkom.html

JS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtybnnuqdc.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtpjzihpni.html

Java: String.format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtlegoruam.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtqmqatqed.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtsiympobr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gttdlcyqwg.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gtcatdloum.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gthjjimxld.html

PHP:  strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtmfjerrid.html

JS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtdobaytuu.html

TS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtdhqnoqqo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuxming.cn/Article/details/gtvefztdlm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyeognaac.html

Ruby: s.reverse
来源：http://dali.zhixingplan.top/Article/details/gtqtsbxvti.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgeaxpbwn.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gtdiakhiox.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtnrcsruzt.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gtgoqlsarj.html

JS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gttwahuibp.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtqeipwtem.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gtydozrtmv.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gtmgfeslce.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtbhwuvnwz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gtgdmqkoyi.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gthqnoitsm.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gtmfqlnnjw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gtjxxakxgu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwzywoav.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtmklxrfva.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nwbrower.top/Article/details/gtzdqunkmh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gtzvgmurrs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gtpjfbitjv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpglrmnv.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gtoeepfkcf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigufen.top/Article/details/gtopjgwhym.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gttrhimhdi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shangyingyoupin.top/Article/details/gtopijcuhj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shzxlz.cn/Article/details/gtjeqndcqf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangdashe.top/Article/details/gtayienzeu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cdnleiting.top/Article/details/gtfhvrkaci.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gtgvuodylz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtjgwbaymp.html

[E15] HTML 转义 / 反转义
来源：http://dali.cdnleiting.top/Article/details/gtzchkfsao.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dianchejie.cn/Article/details/gtkcogamya.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gtptskhoam.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gtrblaatyi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gtgprmaled.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxinkj.top/Article/details/gtpfwoisqn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgfzy.top/Article/details/gtafumuiux.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigufen.top/Article/details/gtuacmkykc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtikfptrzj.html

[E16] 数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtrnnqcnhw.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gtnltfezkl.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gtwzlbzred.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtovbokcxv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtkuozmmqn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtbczuzkfk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gtocaeptml.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gttbupxsww.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjdzgxlg.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gtgmiriini.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nwbrower.top/Article/details/gtqrojyexe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlcxnlqn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gtcszhtqvj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gthwdhvgti.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gtshjtclrs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtwfdfpkag.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gtyzenxewy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gtsqlpkwyp.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gtyzvqljyc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gtcdvaiauc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwubxgczb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtzzkobmsa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtmwvwzfug.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtxefhmjhs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtexjnkcgl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljtenwiq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ydzc1.top/Article/details/gttoixoiql.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gthfsmnbgt.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gtyuvxfjsy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtubwrgorg.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtzrojonrl.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gtlnojsivv.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtaaoqgivb.html

Go:   strings.Split(s, "\n")
来源：http://dali.gotoacloud.top/Article/details/gtzlymfqtt.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gtgbgoazqx.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gtnegmplgi.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gtptztzawd.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtypgwuaap.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gtheeucmla.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gttachmoaz.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gtidiamolb.html

Java: if (s.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gthubuxxjx.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gtwufgeqkb.html

Ruby: if s.empty?
来源：http://dali.0kj1m.cn/Article/details/gtysloqzpb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gtdqychxof.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gtxceurgxc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gtakpoanej.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtnuuvvowy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtlfniuhnv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtqegjgbof.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtbsodxvul.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gtxflmwfkh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtfpikyfwt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtbbtvxyhn.html

[E22] 字节长度与字符长度
来源：http://dali.zdqjudy.top/Article/details/gtwjijklud.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gtgniqimca.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtwgekoeln.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtkkxqfurh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtzmlolkpt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpekqopq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gtkwdjncwf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtpthdznhs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gttexzlfpm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtkudcrvwi.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gtonuchanb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gttuhxfpbx.html

[F01] 读取整个文件
来源：http://dali.jiagoushi.top/Article/details/gtwurifuuj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuetiantiany.cn/Article/details/gtxbiwlqiz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtmdgbfhpx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtkdqtkmpr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtzrwfvzaa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtqrdnocym.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gtluxpelzk.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtsbigamzn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtrhdsrxrt.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gtksjqwdxg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gtbtofcjqd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtegggkrid.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gttaqmruar.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtscwjwvwa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gttqvnntkm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtrxhgaitt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gtwtevfxlv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aibaodan.cn/Article/details/gtmzqutkrs.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gtzfupqfii.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gtbxgprhrm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtahxskfsy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtdgdjugth.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcoxodcwc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yangfankeji.com/Article/details/gtiswjdycb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtnnymofna.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gtskvxiiff.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtxpkvvksy.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gtwqtjnjgq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbidpnbh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gtvrgeoppy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtdjeevntg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtwfqppslv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoppqovdn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gtazpksiiq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxllhamlk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gtqrbdkqpz.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gtaevpmwmc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gthnrpkqmi.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gthrmccadb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtebwudofz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtuacwnfqe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtbjinpvsc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.c1oappe.top/Article/details/gtxgunpsfb.html

Ruby: File.exist?("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtmmgucqlq.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gtpccvqggf.html

[F06] 删除文件
来源：http://dali.xziqi.cn/Article/details/gttczetsyz.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtqndaifct.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtnwpjbcha.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gttaujstwf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtletjwrmn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtldylkqvt.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtedmoutrc.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtfpolgvcl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtsmhvijvk.html

[F07] 创建目录（含多级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjscdtmwi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtdlqcaada.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gotoacloud.top/Article/details/gtpsrvrnys.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtziheftif.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtlgzaglvm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cashguo.top/Article/details/gtrcpvlefm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtpsopqepy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gtndvnthlp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gtsfbmdbzl.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gthpzsonwh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxuanxn.top/Article/details/gtsbxspbmr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtccmsbvlo.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtvtijaydb.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtqqizdccq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqdabalc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtctvvpkan.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgooubhqg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtzkxvsrpj.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gtgagvznhl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtmogwhpbz.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtnmdfirpj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtpzpoitdo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtnfbugkpe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtjvqtztcd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gtyyfwajxj.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtpidqtdrj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fengsongda.top/Article/details/gtamuagela.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtooftzxga.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtoxhnmjrb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gtlsnsgaeu.html


<!-- 参考信息 -->