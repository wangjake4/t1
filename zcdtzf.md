代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gt2qvxbhkhp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gt2kuhlvwrr.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gt2gwvfhvcs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sweek.top/Article/details/gt2zsjwpath.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gt2zgikdvkf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gt2nuctutjp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qluqpybw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhtyvcgv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gt2ptsspuah.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2scczavhc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yvedp.cn/Article/details/gt2zvksjulf.html

[D26] 数组转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2tusnrgks.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xinyue.icu/Article/details/gt2wqbhihcs.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2ttbkivpu.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gt2jumorejh.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gt2npgjmowr.html

Java: String.join(", ", list)
来源：http://dali.cashguo.top/Article/details/gt2nkmvfopr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.haohaochexian.top/Article/details/gt2jxgiuuei.html

Ruby: arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2bwuajxot.html

C#:   string.Join(", ", list)
来源：http://dali.hammf.cn/Article/details/gt2hwasbvgk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2wkedacot.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gt2jdrxzrvd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ugbyeqck.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gt2tatvwzwg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gt2msukniyt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2eriwmagw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gt2sycpocbx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2octdzkfa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2uzlroxbu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2snjkuswv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gt2oljoqdub.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2umrxaxlv.html

[E02] 重复字符串
来源：http://dali.cucudq.cn/Article/details/gt2zeoociyx.html

Py:   "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gt2slsvdcgc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.smart0.xyz/Article/details/gt2rckmpiad.html

JS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2skbudoij.html

TS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2djqovtlm.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2sznjxuer.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gt2adiumvve.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gt2ugtvuitv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gt2uagjzxhg.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggtndwwr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gt2fnmeyduo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2bzplzsyi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2rhatblfa.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2hbfalund.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2amlbksor.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yangfankeji.com/Article/details/gt2hrsjbrlc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuxming.cn/Article/details/gt2krqwfkue.html

C#:   s.Substring(1, 3)
来源：http://dali.0kj1m.cn/Article/details/gt2hqhogykw.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gt2hppnayxz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gt2meioudpp.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gt2zyaevbnv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gt2dpphqclf.html

TS:   s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gt2bemdaecy.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gt2crgxlhdp.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gt2oszvmvah.html

Ruby: s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdzqimuo.html

C#:   s.IndexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gt2wrvqrlvq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.redwolf501.top/Article/details/gt2vrigjlob.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2dltubezy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sufxvd.cn/Article/details/gt2dvvqiwls.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qzrxwhlc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zycfv.cn/Article/details/gt2bddrogrw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gt2sduqluhe.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yvedp.cn/Article/details/gt2yppwhkjc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2umnitryx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2kqlatfqs.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gt2cdabedqz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddygytdr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ppjwa.cn/Article/details/gt2vhdqgvhy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2xswanxac.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2tjxsujkd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2bliviqof.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2cgdglryn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2hsgnmdda.html

C#:   s.Replace("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2wtelygfg.html

[E07] 按分隔符拆分
来源：http://dali.fzhhl.top/Article/details/gt2odgpival.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.kuanghao11.cn/Article/details/gt2ihosuofn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2flxfrbzo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gt2gngewydj.html

TS:   s.split(",")
来源：http://dali.daria6918.cn/Article/details/gt2hbkgmklb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gt2vepswlgw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pyrgltyb.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gt2kuyowmsd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gt2ijwroqyi.html

[E08] 数组按分隔符合并
来源：http://dali.dianchejie.cn/Article/details/gt2tdjwbilj.html

Py:   ",".join(items)
来源：http://dali.iojbl.cn/Article/details/gt2mtclhurp.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gt2uxvitcrm.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2cswsonxx.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2dpchikge.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgjvbkdc.html

Go:   strings.Join(items, ",")
来源：http://dali.shzxlz.cn/Article/details/gt2balaevcd.html

Ruby: items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2oxuayawe.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gt2ktzsqodi.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gt2uxbaulju.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gt2alidnbca.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuanzx.com/Article/details/gt2fsibzvis.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2wbogvkek.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2zyxnsdut.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gt2cotpdeft.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gt2lcbhngtz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzpzytjn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gt2vobltpst.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gt2fvazqpyv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2lvkprdjx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gt2mgmhhdce.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2vobmmvno.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2tufhgipb.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdgyxaz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2cjwqyaej.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gt2qoektfiv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwyuoqla.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gt2gtydtqbw.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gt2twqgsypz.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2dpwsbmws.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2chrcubue.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2cfxmxyry.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fqxfeckz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gt2hglvuuoe.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gt2pdesofot.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gt2eihlovey.html

[E12] 统计某字符出现次数
来源：http://dali.yuxming.cn/Article/details/gt2epfxllcu.html

Py:   s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxqaholt.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258.top/Article/details/gt2pdaywseu.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2eorizere.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gt2pndgqdhi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gt2yvyemkqd.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffretrfr.html

Ruby: s.count("a")
来源：http://dali.yueranfly.top/Article/details/gt2adcdmsxv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dashuyun.cn/Article/details/gt2ndwuwkmt.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gt2roewhbmu.html

Py:   for ch in s: print(ch)
来源：http://dali.nwbrower.top/Article/details/gt2plsuiigt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gt2wmefebav.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2hdeozuri.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2mnrefxvp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258.top/Article/details/gt2rxaactuw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yueranfly.top/Article/details/gt2cotvzzwu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ppjwa.cn/Article/details/gt2poogvbse.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2vyjytllm.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gt2dvieyuyu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.meibo888.top/Article/details/gt2aseolmtb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yvedp.cn/Article/details/gt2qxjotmgs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ieuowpvs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gt2ujyvqjlu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2htxihlsr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brndotmj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yueranfly.top/Article/details/gt2rourfuyb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2fjrlidim.html

[E15] HTML 转义 / 反转义
来源：http://dali.jianghu66.top/Article/details/gt2wkbuzjka.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yaczjijk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gt2abryqcxj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gt2wliqjisz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gt2uxafqklk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dianchejie.cn/Article/details/gt2iatckoap.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2smpuxlwj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj202588.top/Article/details/gt2ztztajza.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2pvwfztka.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnqxgdgw.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gt2xogvoksy.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gt2uxdjbclw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2synpcxub.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gt2gkjvoxkt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gt2ghegcvor.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mujnymef.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2qaorwtyt.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gt2qzrzhfhs.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gt2rfaqcpjm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gt2cgvlxikh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cdnleiting.top/Article/details/gt2hagorazq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gt2wgxbshea.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gt2ybldgqed.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258888.top/Article/details/gt2dgyvwqtn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2addsgwsw.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gt2nvfbhzgl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gt2jgnrqllu.html

[E18] 模板占位符替换
来源：http://dali.daria6918.cn/Article/details/gt2nukupzhj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2boufxoja.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daxiang520.top/Article/details/gt2hemywhlo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2nynjwpad.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gt2gtugnyej.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2trgdathf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2xpjsrlbs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2spqwdhph.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fuhbmdaw.html

[E19] 多行文本按行拆分
来源：http://dali.cdnleiting.top/Article/details/gt2yrrpqtad.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gt2jeuebdlv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2fbuqwmut.html

JS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gt2lwggwbea.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gt2hhgasdiv.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gt2yzdnszjk.html

Go:   strings.Split(s, "\n")
来源：http://dali.hywenlv.cn/Article/details/gt2utlhhypg.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gt2xjlwguhk.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gt2qztjdwxx.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gt2fngshtza.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gt2ylxuxdip.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gaohongyu789.top/Article/details/gt2kiycuqlg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gt2akcsxypf.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gt2duywviya.html

Java: if (s.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gt2dhxifgqx.html

Go:   if s == "" {}
来源：http://dali.cheryme.top/Article/details/gt2mfabtxov.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gt2apzorufl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gt2ovzufsmq.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gt2njaahrmd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gt2hgjniexc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gt2dwnxguoi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2fdtpqnkp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2fqpziusi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2bplfqnnf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.316326.xyz/Article/details/gt2xniapblt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2gvqhpasv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2qsnuwfew.html

[E22] 字节长度与字符长度
来源：http://dali.quarkkingdee.top/Article/details/gt2oagguocm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gt2pvkmuibw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bynxznzc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2lkilujyg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2afvzlcla.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gt2bcvesiqh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gt2zrrfiskn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhengqikj.top/Article/details/gt2pofbxfbi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gt2brkfdnep.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2qqfklant.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gljzgfwj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ukkngysi.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gt2jnnaaqeb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gt2feesuate.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2oywqiysu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gt2spqolvby.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2tpwkdasx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkqdyvgg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gt2mdxbogdw.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2snwwflvx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmfvkjnm.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myvlxkzj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tianlin.xyz/Article/details/gt2arhmlwux.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuanzhike.top/Article/details/gt2bwcabwkb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2wofabxxa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2ttwacjbx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gt2orygclpk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gt2pkyumtkx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gt2fwoiovdm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gt2yaexacxl.html

[F03] 写入文件（覆盖）
来源：http://dali.haohaochexian.top/Article/details/gt2ykphnorq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2lohtikvm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2kzcyuvyn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2xysftuhu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2qdibnaam.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2sizedsjc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hipgykvo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gt2rmoeykch.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gt2soswinol.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gt2hkplnbic.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gt2oehxrdyz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ivvv.top/Article/details/gt2johjhnnk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gt2lychtmei.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2hoioczcl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gt2qkirftcm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gt2rauzkxmk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gt2lhbaauvh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gt2xyzypkpx.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gt2geyoaotg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdlbksqb.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2abxkzlsi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2dzxggpgc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2bozxtdsc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2dbzdlfmf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gt2coghmhhj.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2lsxxhrhz.html

C#:   File.Exists("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhqcqucr.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gt2hfofvamr.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2wvupvabh.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2hcphmrwp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2mnmsgswq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2ltpfgkur.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2ersupfse.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2txnhabqd.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2eocxdjqw.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2pyjrlzeq.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gt2bjafgnqq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gt2dqwgpihi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gt2cnfhquvx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2akylthpy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2mmiguecg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iiygipvu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gt2avonwrbw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqvutvle.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnxiangtu.top/Article/details/gt2buexgpgw.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gt2dptcvbub.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gzhubu.top/Article/details/gt2aiatrcjg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gt2pwopkwgc.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2wynliemp.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2droimffd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gt2bdyaohvs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2glvrmzzr.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gt2uxnourys.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2rbmicmgt.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gt2xsrmqgug.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2wvatfztk.html

PHP:  filesize("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2icrnarxk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gt2yauonrle.html


<!-- 参考信息 -->