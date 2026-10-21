代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gzhubu.top/Article/details/gtnxpjwtzj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gthukhefqb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gtsaybmrax.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtklqleixi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zycfv.cn/Article/details/gtoiipvjgu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gtfjmzmkzp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigufen.top/Article/details/gtcgxgclyq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtxqqcujop.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gtpuymwwkq.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtebbnlyac.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gtsxgipzbc.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtaekteaog.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtuvlexnls.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtaqunkqek.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.meibo888.top/Article/details/gtzxymecpv.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gthubxjgiu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yueranfly.top/Article/details/gtonfrziyg.html

[E03] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gthxvcsenc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cdnleiting.top/Article/details/gtqmcipthm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtajhwusup.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtzltlnexj.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtczugeyov.html

Java: s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtbtgircdf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cheryme.top/Article/details/gthpgegfwd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtufepkgws.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gteelfbzpr.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gtqspdziwn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtimmwukcn.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gthihdvafi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj202588.top/Article/details/gtiynrebai.html

TS:   s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtgjldnout.html

Java: s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtwgmrgszd.html

Go:   strings.Index(s, "x")
来源：http://dali.guowangkeji.top/Article/details/gttmysvagz.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gtbhanuhpr.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtnkqrkrfp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gtecnysdiv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gtxafzropi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gtjeufzmzg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtuzkayfuh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtjsimwgub.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtbdxpmcfz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sysykeji.top/Article/details/gtsqmimvly.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gtcltahvcf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtrtobjvmx.html

[E06] 替换子串
来源：http://dali.ehwqpu.com/Article/details/gtvhbczulm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtfcyzwzyb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gtvyyrhioc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtdtzxmiut.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtvkfazycb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtrgnynqnu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtnokpbgfc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtudznduxc.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtbplimisp.html

[E07] 按分隔符拆分
来源：http://dali.jqgufenzy.top/Article/details/gtmcewupvl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gtzyvauoyo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtytjdbqcv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gthmeaibkd.html

TS:   s.split(",")
来源：http://dali.bjfxy.top/Article/details/gtysfiffun.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gtvyjveypo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gtkecmyphk.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtaiyygegf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.andypj.xyz/Article/details/gtpchhxavz.html

[E08] 数组按分隔符合并
来源：http://dali.cdnleiting.top/Article/details/gtwaiyyhgb.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gtglotcwcm.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gtvjbsndhg.html

JS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtqybvmfjt.html

TS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtelisymgx.html

Java: String.join(",", items)
来源：http://dali.yj20258.top/Article/details/gtnkidxzpd.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gtaugfekub.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtzojjiahw.html

C#:   string.Join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtccicpmxw.html

[E09] 去除所有空白字符
来源：http://dali.smart0.xyz/Article/details/gtrqebqdwp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aibaodan.cn/Article/details/gtbphmluok.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.andypj.xyz/Article/details/gtqlstmygg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtmnqrvigs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtpjfynnuy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hammf.cn/Article/details/gtpzzzrtip.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gotoacloud.top/Article/details/gtwsmsquyp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gtasjrddjd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gtgupdvlxd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gtheovostm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gttgoporqh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuxming.cn/Article/details/gtqhejyzog.html

JS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtjqnrqzop.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtojsyppsr.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtttxnnyzq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gttxqrblai.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtksgyluml.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gtpeiroifg.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gtcqiafwdh.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtuforpkql.html

PHP:  strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtbcvznnds.html

JS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtzvmgoqud.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtqpoqdogi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gtpuebycav.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdplewku.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtdrvskjyx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gttvrrxmmh.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gtuktyikgg.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gttpxzhxhe.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gtsfalfdcv.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gttbqfogaf.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtlovesicc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guannengcc.top/Article/details/gtofetxpzc.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gtlrgvzvzq.html

Ruby: s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtlemhzvvm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtkuthhnly.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gtsfwvgxbw.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtyphycczq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gtzlckunsr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtrrvfhfew.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtaalnzxsl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jianghu66.top/Article/details/gtkpqzvsdq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cashguo.top/Article/details/gtukykaeln.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tianlin.xyz/Article/details/gtxpnjgywk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gtyjxgublu.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gtwbknmato.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gtyykmqfse.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gtwmxsqlvj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dashuyun.cn/Article/details/gtuauqhnvm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gtrmqdibfw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtupslilgj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gtndnnxfyq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gtekgsurfw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtzhpygbmm.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gtklcmlnfe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gtzytpouwf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtdlutuoop.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gtwnluitij.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gtolzswjnv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ydzc1.top/Article/details/gtwfbknfzx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusqrrlhi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gtkiwejolt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tanke756.top/Article/details/gtdleozngm.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gtgzjoleir.html

Py:   f"{1234567:,}"
来源：http://dali.shuidangran.top/Article/details/gtblutlgos.html

PHP:  number_format(1234567);
来源：http://dali.chenjidiqi.icu/Article/details/gthjqqxkvt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtwacgavyk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvwefvbf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtewtiebds.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.redwolf501.top/Article/details/gtpoblaayu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.svipenyu.cn/Article/details/gtypvvnsaw.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsmvndzo.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gtlekyfdga.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gogol.net.cn/Article/details/gtldiufpmz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gtgxmkknvu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtylemfmfh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtrognhqyl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gtjzlyiajo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gtckpyxhsi.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtniwqyrek.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtuthvslcb.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtwlggumyr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gtgntfnbwd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gtucwvaujo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuklvmlbx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtoxfaqyht.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtmkwnqbho.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtxvzcmhfy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtmtzgvbyj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gaohongyu789.top/Article/details/gtudubbyrj.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigufen.top/Article/details/gtmwbwqhcr.html

Py:   s.splitlines()
来源：http://dali.xylfe.cn/Article/details/gtweihfhxm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gtwlmwdadv.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gtkkilksgg.html

TS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtqaerfwcj.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gtwejknaua.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfvhfbsx.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gtlqlnyidl.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtkdlxkdjp.html

[E20] 判断字符串是否为空
来源：http://dali.ppjwa.cn/Article/details/gtyfwvpedj.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gtfuwaqvqp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxinkj.top/Article/details/gtivqwnmjm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yongpay.top/Article/details/gtzpgcztjr.html

TS:   if (s === "") {}
来源：http://dali.cucudq.cn/Article/details/gtrwoxuuhw.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtvcvcbdyf.html

Go:   if s == "" {}
来源：http://dali.gzhubu.top/Article/details/gtgknmuljs.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gtcirvyifh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtwqdxbuoi.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gtuadikkij.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtzmmzezqo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtyivhlily.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtxkfmilpp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtqjwdwydq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtinckarux.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkxeujdb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtslkqiacb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtcatrqqji.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gtdtfrdqaz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ppjwa.cn/Article/details/gtsensmbav.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgnzqkbe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtpjysaxck.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtmtvihqat.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gteweppkpf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtzrqqdiih.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtqlzzitss.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gtarxuvvjd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfptyqndq.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gtfknwnlfm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gthszbhudd.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gtlfnnlkxu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dianchejie.cn/Article/details/gtxkxelbdg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gtoqurhxog.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aizwys.cn/Article/details/gtqmhlurmm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gtebaihkrh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtmuoekgfd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gtnizgvtdj.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtlcqabmgh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtgprsdzmt.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gtufyyrcgr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtcugysbwc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtcvzeilzd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvfavbpnq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwoktujvk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtuzfkvsew.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrmeyvqb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gtmtwbdclf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gtovkmbcve.html

[F03] 写入文件（覆盖）
来源：http://dali.jianghu66.top/Article/details/gtvbixvkxa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aizwys.cn/Article/details/gttbaztcsr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtgqhczcyl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtnqatvqhq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtrpszqywz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gtclyhyzbt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gtsfqrsrhq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aizwys.cn/Article/details/gtitwjtlpc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtbsnsfhse.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gthvbaomog.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gtqyqzrixu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gtlvblcfgf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtqjqwgygs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gtquddikib.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtcngvlhtu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gtbogkduxv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cheryme.top/Article/details/gtrrdvtnep.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtqbfyokig.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtgpaqlxvg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gtkuiytbmp.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalkfuoow.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtfuwgifay.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtvopojyts.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtafziwfwq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtunyucqyb.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gthjkejlcc.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gtuuxwjrhe.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gtndsuncmk.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtpehddndc.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gtuvhmymjj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtzxxshllo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtsmmtvqnt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtlwavicdo.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtddreydtx.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtzlupxrxy.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtyodzvyep.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gtcprglzzl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtelxpokcy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gtkmrqqvln.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtverdiglf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtqiwvopwm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zycfv.cn/Article/details/gtaqbuhupa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtpvxmgufy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtdwunjmnu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gtllujdxqr.html

[F08] 遍历目录
来源：http://dali.pengpengdd.cyou/Article/details/gticfclhyw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gtqoikhzbs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ehwqpu.com/Article/details/gtpkydujwe.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtcwnrktoj.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gtmrpcjkdi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtziuvrjvx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtvmrsbsiz.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gtaoxwvlqg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gtwrculfuk.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gtcywycvvu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gtnoksrkxg.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gteauepcdh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtkvuodedy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtjxtdvqwi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gttbwdfslu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gtpkcrxgxs.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtwabhilmf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gtuawvobrs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtnarfxydl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtcvspihbv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtkrpehfml.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtdaigdtsq.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpustcsth.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtslirfrov.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtlrjseqdt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtvuozpxnq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtlqyhidpp.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gthdbonhvy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtqqxlbgqj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gtnzcnsadx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtalkdqroe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtxnlzfref.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gttqqeajvd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtgjlkzqxk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtpwuiciri.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtvcjkcmiu.html

[F12] CSV 读写
来源：http://dali.ivvv.top/Article/details/gtulbfhdgx.html


<!-- 参考信息 -->