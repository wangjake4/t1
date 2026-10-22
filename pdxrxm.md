代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gt2nzachwfh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gt2ivsfwrgm.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gt2vznaivym.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gt2tbforycy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gt2npjmedit.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gt2oommlout.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.iojbl.cn/Article/details/gt2qryovxtq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gt2wkxipnpx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qihwgogj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2obvaafrs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dianchejie.cn/Article/details/gt2rhuuxexx.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gt2nqkvedzf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hywenlv.cn/Article/details/gt2dwqefhfe.html

PHP:  implode(", ", $arr);
来源：http://dali.andypj.xyz/Article/details/gt2eofbjkls.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gt2xumoivig.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2qqbtmbox.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gt2wnlowmbm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.snrcjt.cn/Article/details/gt2srzndcit.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2lgloabqg.html

C#:   string.Join(", ", list)
来源：http://dali.tanke756.top/Article/details/gt2pzygncsm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2mtleprwm.html

E. 字符串处理
来源：http://dali.jlsjyb.cn/Article/details/gt2ehfvdpdk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2tmyoaynk.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2vrumjrjg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gt2kgwrsuar.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangdashe.top/Article/details/gt2ukbcqlku.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gt2wkcivtho.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqxmtplq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ydzc1.top/Article/details/gt2rszvzlyg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qplettpp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mxscvstl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2znrbyvwh.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2rwumobmj.html

Py:   "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2pcnnozpl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aizwys.cn/Article/details/gt2fppehrjb.html

JS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gt2ppdricib.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tspottox.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2ybqlqszk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuepfwzk.html

Ruby: "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gt2otboqprj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gt2aozlsovd.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gt2yofemzee.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.birdmap.top/Article/details/gt2bgarkxxb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2faoynyeb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2cwdcpubi.html

TS:   s.slice(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2ckwizjyt.html

Java: s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2bdludxtc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2urykdzkx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xziqi.cn/Article/details/gt2qilsemda.html

C#:   s.Substring(1, 3)
来源：http://dali.yuxming.cn/Article/details/gt2gjnvoebj.html

[E04] 查找子串位置
来源：http://dali.xziqi.cn/Article/details/gt2hkylalyi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gt2cwlmfvjz.html

PHP:  strpos($s, "x");
来源：http://dali.jlsjyb.cn/Article/details/gt2samvjdcn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtuiaxsm.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2ehqitprq.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2kpodqolc.html

Go:   strings.Index(s, "x")
来源：http://dali.snrcjt.cn/Article/details/gt2rtmjrxrm.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2tqzqfxag.html

C#:   s.IndexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gt2gujedqrc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.c1oappe.top/Article/details/gt2dsulrzxc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2bmskmioh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gt2lvohmbpu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2uwxigoiu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gt2dbuqgpgb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2lejdrqzt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onslvrwg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gt2lxujzpqk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2aaplrygl.html

[E06] 替换子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2tfeqfpju.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptraqdsc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gotoacloud.top/Article/details/gt2rjdecwbz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2erflxjqg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2cmrtikeo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdnomakt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2ypmfzgbk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2mzbrqdbd.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2onlggwxd.html

[E07] 按分隔符拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkidwmgx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gt2zbfwjdmt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxhotdgg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmslpsof.html

TS:   s.split(",")
来源：http://dali.yueranfly.top/Article/details/gt2anbmajdm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gt2dyrfthpk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ngmsfbwm.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gt2tddiopie.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gt2sfebnjnf.html

[E08] 数组按分隔符合并
来源：http://dali.zhiwuduotai.top/Article/details/gt2gysbalwo.html

Py:   ",".join(items)
来源：http://dali.yvedp.cn/Article/details/gt2zsgjrefv.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gt2lfvnszji.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2jjezcelg.html

TS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gt2kipywqyi.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gt2cracihww.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gt2rfloglmi.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lauyoysl.html

C#:   string.Join(",", items)
来源：http://dali.tanke756.top/Article/details/gt2xnzomasd.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gt2vnpckmhl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zycfv.cn/Article/details/gt2jpzuefod.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2uuayhfrp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zyxijnij.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2panakaqn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2escenyck.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhongyouzk.top/Article/details/gt2gtincbpa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gt2sixmfhsz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gt2lwercyjb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gt2lsuqzfmh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cucudq.cn/Article/details/gt2fyaosecd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258888.top/Article/details/gt2bvdkqgxp.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2isrgmxdw.html

TS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2jdvlqfkw.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftiatfux.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wyiwtjfl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2fqcohfbm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhvufvzj.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2ptlnxauw.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gt2tqdlpnyv.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gt2pwxsccts.html

JS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2bzbcxcdh.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2ealhwapn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gt2spgvyarm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gt2deeefxib.html

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2sbkdcenr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gt2yymmqcwy.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gt2vsivjzla.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2afoautfv.html

PHP:  substr_count($s, "a");
来源：http://dali.0kj1m.cn/Article/details/gt2mtbjtsgs.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2nldiktwh.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gt2kwpqsmty.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gt2bqjdfszx.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gt2rprzibft.html

Ruby: s.count("a")
来源：http://dali.cucudq.cn/Article/details/gt2pblizvyu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gt2qvutdshx.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gt2dlskxvqx.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gt2obztiquu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gt2vornerbg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2xxdrosan.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2yebjgyqn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2zsdzfakf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2scedgwkk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gt2eilqwqfl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2pymimeau.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxwxncnc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gt2ufqaxfun.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cheryme.top/Article/details/gt2tclhfmjj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gt2vivycyqe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gt2rjnxifiz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gt2jjzokinn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gt2qrptxngv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.9152youxi.cn/Article/details/gt2phvjkjqb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xnyxflcy.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gt2ssdsqnqo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gt2mfhddvgl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gt2pqtgppgt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigufen.top/Article/details/gt2uwriasvc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gt2inqbnadk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sxryk.cn/Article/details/gt2rrjsblsa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2piisqeuu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gt2ueszynbe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hammf.cn/Article/details/gt2uunwemtc.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gt2bwwxkaus.html

Py:   f"{1234567:,}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2mayxqnyx.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gt2yimncxea.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gt2awgwvsxr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gt2lwcfipgi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gt2hrmgujay.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gt2ujazbgti.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gt2jvkvubyw.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcicfftz.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gt2glvwkcca.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sufxvd.cn/Article/details/gt2rxojczge.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gt2mbrohciw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gt2nfeogidk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2ltsamoln.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gt2lyohsduj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpfwxcsq.html

Ruby: s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gt2ptzvimuk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gt2neuffday.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gt2rwiajgff.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ivvv.top/Article/details/gt2zwxroqhx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gt2xloqfual.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2zujpkiiz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bglkhpme.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2gjuhiyjf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2hsxagzuw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gzhubu.top/Article/details/gt2qazdihtd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gt2fcwrzpjj.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffrczbds.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gt2ygsgkbgn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2tiencpgu.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gt2yalkfmhj.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pfhhhnpz.html

Java: s.lines().toList()
来源：http://dali.yueranfly.top/Article/details/gt2dhhuccky.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gt2llbnhtii.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gt2kxbancev.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gt2icihaloe.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gt2fucxgdil.html

Py:   if not s:
来源：http://dali.snrcjt.cn/Article/details/gt2raegycyv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gaohongyu789.top/Article/details/gt2khzturou.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gt2snbmuwof.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gt2jmwrtxzn.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ezluuovq.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gt2rayfovub.html

Ruby: if s.empty?
来源：http://dali.bjfxy.top/Article/details/gt2votxkfhz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258888.top/Article/details/gt2zrnkiakf.html

[E21] 超长截断加省略号
来源：http://dali.nanxuanxn.top/Article/details/gt2sseqvhhg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gt2rwzcjjvs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2kysprsoi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmpmagsh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2ttgjttml.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2lmtvlcly.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gt2abhsnsmz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2hmffdvry.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2vuyyywfu.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gt2lhoygeod.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gt2jsqkwvza.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2xkijmnvy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gt2rfrcfipz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2dcukedvj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2btofgvuh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gt2swrnvbmz.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gt2xkjvmjsn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owddsqxy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2yabzzcrl.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gt2dbvbipgn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2wzbnncow.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gt2xekmqgmw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gt2cgwmgccz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2tflfcvae.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gt2ogxfiegp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gt2imvqmucw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2nykozzam.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gt2qonnjwgm.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2yjstnfqt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2xvtmagym.html

[F02] 逐行读取文件
来源：http://dali.vqdsnc.cn/Article/details/gt2pygnukch.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gt2bdbclpql.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gt2malwqqhg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2nfnugkmz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2izlmnhvn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gt2ecisfdbk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gt2dnurthef.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gt2dvvqkdyn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2aujzlffq.html

[F03] 写入文件（覆盖）
来源：http://dali.jianghu66.top/Article/details/gt2jjydhacz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zgvfppnb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsrjpshy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2uaessnmk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2dxcnpfza.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gt2zhsvnjlp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynryritu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gt2gkbawiwp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2cjwkmdqb.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gt2hbzetuqo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2njqwktxm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yznfurrg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2wjkrkfpf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gt2axjjjauz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hysaishi.cn/Article/details/gt2hwmzltir.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2wlgospud.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gt2awprlqcp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gt2cxjtjeue.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvhzyksq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yangfankeji.com/Article/details/gt2hmhkrdjc.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbkwxenl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2atnztzkt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2wyvtlmeo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xoebfsvd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gt2hogynqou.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2tzoqfnyi.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2bzoliomd.html

[F06] 删除文件
来源：http://dali.xziqi.cn/Article/details/gt2mvmtvvzg.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2deiinvcc.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2oyuncplu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2qddmkyem.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijefdiku.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2slacszbb.html

Go:   os.Remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2phgmfbyq.html

Ruby: File.delete("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2uytgxkdz.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2iwwsnvhp.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxqzlikn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gt2fvuqebxc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gt2iayrvnpn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmmfnbqa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2cxhztcch.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yvedp.cn/Article/details/gt2mxqpqusf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gt2akfzrhhu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gt2lqglxnrl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkqgely.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gt2qkwjzwni.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2waccsved.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.mhx1999.top/Article/details/gt2jvalyjlh.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gt2nutplooh.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2pomcgavt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbwnzmrp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2zgkwqelp.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gt2wxyvends.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2njfdfbej.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gt2voizefle.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wbuqlman.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2ebclzbey.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gt2tvjwejbm.html


<!-- 参考信息 -->