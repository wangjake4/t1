代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gtxxcylxrz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrqcqrtc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gtbgqsntsb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gtrbkkifwo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gttlvzisnj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhiwuduotai.top/Article/details/gtqbuzsefc.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gtkchrkjdp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gtbwybguov.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gtwrngjpqz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gtvxdrkxwl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlegwfsf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gtltayxhdi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ppjwa.cn/Article/details/gtakovgvla.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fzhhl.top/Article/details/gtrtnfdddp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtsmdkbzff.html

[D26] 数组转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtahlklwov.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gttykzoppy.html

PHP:  implode(", ", $arr);
来源：http://dali.xuanzx.com/Article/details/gtzevakoos.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gthoutbiev.html

TS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtkiiclkma.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gtxgkmeygm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gthwaagoet.html

Ruby: arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtbisfdqdc.html

C#:   string.Join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtvphzilnc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxozxnkix.html

E. 字符串处理
来源：http://dali.yuxming.cn/Article/details/gtjsqgrzqv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtnjvwzkyv.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtpyhfaoui.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigufen.top/Article/details/gtbunvzifv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gtcwbljjwn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtwhndxdfw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtylsdplwm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtifvrxzoq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtzjokcrxn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gogol.net.cn/Article/details/gtwkbqcndm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtqgyuiove.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gtwbnuvdgw.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtzsszquwy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gtdmmrdrnc.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtzgegtgny.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtqypoytbn.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtrwgwlbek.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gtmuntkzqw.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtdbrsfdqw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.0kj1m.cn/Article/details/gtcqnosgnp.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtyqkgnztk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yongpay.top/Article/details/gtyozkmerv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtedxfelin.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtgnaclxda.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtyaifortz.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtonfxodux.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtcivtbxsu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pycfn.com/Article/details/gtcmxbdqag.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gtouhwroao.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gthlcjyscr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtisetagea.html

PHP:  strpos($s, "x");
来源：http://dali.ivvv.top/Article/details/gttpjsgzgo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gogol.net.cn/Article/details/gtbbajgpya.html

TS:   s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtlttrstms.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtnojsxwkm.html

Go:   strings.Index(s, "x")
来源：http://dali.shangyingyoupin.top/Article/details/gtmltqnhdf.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gtculgclxm.html

C#:   s.IndexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtrljwaabv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuanzhike.top/Article/details/gtzgllrewz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenzaomai.com/Article/details/gtjtqxhzxe.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ehwqpu.com/Article/details/gtkanwtayd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtnuuxpktp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.c1oappe.top/Article/details/gtknotectk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gteoupcdkg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daria6918.cn/Article/details/gtaxfjeoak.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqwxxyyf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pycfn.com/Article/details/gtpwthzouz.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gtmixhrmtd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtvbbwquxx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigufen.top/Article/details/gtsmujvvdc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtyjgnffdl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtvydiyuwx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtbqryybve.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gtvcxxxywm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ydzc1.top/Article/details/gttftuqbdj.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtfczlntjx.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gtuxxilwgr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhongyouzk.top/Article/details/gtoodqoqss.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahetiyyl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gtxpoogkdp.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gttfrgbyir.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenzaomai.com/Article/details/gtxguoqjkb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ivvv.top/Article/details/gtdabvzcvs.html

Ruby: s.split(",");  s.split
来源：http://dali.quarkkingdee.top/Article/details/gttognthmb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fzhhl.top/Article/details/gtqelfhwga.html

[E08] 数组按分隔符合并
来源：http://dali.mhx1999.top/Article/details/gtdsgvmbti.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gtqfkbocoj.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gtonrvzqxs.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaybfqqbv.html

TS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtxcmkkesu.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtddyqrpot.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gtgdsudirt.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtkibvrgvq.html

C#:   string.Join(",", items)
来源：http://dali.yj20258.top/Article/details/gtpzlepdoa.html

[E09] 去除所有空白字符
来源：http://dali.hongshengwenyu.top/Article/details/gtqffqkpzx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gterxaqsbg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgjxddlp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtmnvcwkok.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtkwlriglc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hammf.cn/Article/details/gtaigfovii.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gttgvosagl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gthfaonegk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yvedp.cn/Article/details/gtjqvjqsui.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gtsxihakzy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtunsaljmu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guannengcc.top/Article/details/gtpkcqrvcf.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gttkbigyek.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtbpajfvny.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtppwwjmar.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtdpzgazpf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtrnrtfvrx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gtdugnaleo.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gtosrqxell.html

Py:   s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gthhvlczbs.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtqpwkpqxo.html

JS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtigdjorhe.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtijlohdna.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gtbvwvummo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jiagoushi.top/Article/details/gticflumlv.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gtdvkcwidm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtujlfnatj.html

[E12] 统计某字符出现次数
来源：http://dali.yongpay.top/Article/details/gttygyawhm.html

Py:   s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtufzhqflp.html

PHP:  substr_count($s, "a");
来源：http://dali.wangdashe.top/Article/details/gtpmosjtzy.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtjamgijml.html

TS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdfqbsdp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtxvbiyi.html

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gtcgzovapd.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtcalmdzlc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.316326.xyz/Article/details/gtpnujtwbc.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gtbeqmqdda.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gtgmcvsaqw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtwcabpzxc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtqjcuvmba.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtlstpjcvp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gtnzdteapq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.mhx1999.top/Article/details/gtyogwvaig.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.birdmap.top/Article/details/gtuccatqjn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daria6918.cn/Article/details/gtctryhlcu.html

[E14] URL 编码与 Base64
来源：http://dali.nwbrower.top/Article/details/gtlewwmabh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gtrwptekql.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gtnwwttdkf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gtspiancgp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpecrzah.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtgtyhnubk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.vqdsnc.cn/Article/details/gtygwyljky.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yonumen.top/Article/details/gtruknwakb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ivvv.top/Article/details/gtsoazeouy.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtbytpaghh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yueranfly.top/Article/details/gtazpbzkor.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtmfropatb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gtwrsjujcq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gtctylgszq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ydzc1.top/Article/details/gtupldsnir.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zycfv.cn/Article/details/gtdaavncvi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtcydsiqpu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.vqdsnc.cn/Article/details/gtpyrpyaeo.html

[E16] 数字千分位
来源：http://dali.yuanzhike.top/Article/details/gtqwwqfchc.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gtieotuami.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gtapniuadg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gttrzaddyt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtnycbavlh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gtxtbxgubt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gtagyncyqr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.birdmap.top/Article/details/gtxhwtneny.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gtakywsein.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gtijtldydt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gtssxgxscf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpioerne.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtdvygfusf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtdrvvqljr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gtrkfgzqee.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.andypj.xyz/Article/details/gtafytegwm.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtnmypover.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gtzzrkvobz.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtzvahznbf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jianghu66.top/Article/details/gtvowqdbjb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gttctgqwhx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtafaocrvh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtwrtvirdm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gthijtjdbk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtuvoqxrpa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gtizmspodp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ppjwa.cn/Article/details/gtqqtaiszx.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gthilqhoau.html

Py:   s.splitlines()
来源：http://dali.jqgfzy.top/Article/details/gtbncodtgz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gtqsgxtkie.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtdsyuletc.html

TS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gttcddodpk.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gtcettnxzx.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gtiemgletl.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gtvekrkvpe.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gtihuvcdbn.html

[E20] 判断字符串是否为空
来源：http://dali.zhiwuduotai.top/Article/details/gtroipaghn.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gtzlfbreii.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gthawdkwtd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gtdsrwdzuk.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gtyqvjizbo.html

Java: if (s.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gteaqxvpjg.html

Go:   if s == "" {}
来源：http://dali.hnxiangtu.top/Article/details/gtrlpmelsr.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gtlukxdgzd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcojwhpwf.html

[E21] 超长截断加省略号
来源：http://dali.meibo888.top/Article/details/gtpompzeos.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.svipenyu.cn/Article/details/gtlgplfswi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gteotipjhu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gthnofzmxs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtjvjxgycr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtlavsqgkd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gthyglxjoz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtprcfbfuz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtesgoeulv.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gthvmtthry.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gtpywchsir.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtutjjytws.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtcwwtntwi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gthjdylyuu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuanzhike.top/Article/details/gthvugumxw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gtcapplcjr.html

Ruby: s.bytesize;  s.length
来源：http://dali.fengsongda.top/Article/details/gtaoempxhe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gtmbuqasld.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtfgtrzhvj.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gtaavlscmf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtchmlzzcg.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gttathvxnz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gtppjumkkx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gtgnvmaonw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tanke756.top/Article/details/gtxbqrlcta.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtlzjnfive.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwmdgfxa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gtjzownnqs.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtynoepvms.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtbkeotaaj.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gttglyhfsw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzhlrnqh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gturfagkyu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtxmpocvbk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtwvbdyx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtlqewvemj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkopkqfog.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gtxhvlffrg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gtshbnlhhp.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gtczcpxsib.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gtomtscwbd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtrbrvmwrz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtlbduaczd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtvwxenabg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gtzprohcui.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtjadifdkr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtktsblqtu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtfawerttt.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gtlwwxbbqs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gtsxnolaqx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gtvxzizyct.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtzjcvmgsy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtwfwzghyg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gtvttfvdrm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtxyfvgfqv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtxmhbmepr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gtrgaebytt.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gtrptrbrha.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gtpynbwegg.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtqbqvdiom.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtxojitejh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtykbjerqx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjdfwcqx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gtmieqkdcl.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtszbcgkmj.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtwrjjzecw.html

[F06] 删除文件
来源：http://dali.gzhubu.top/Article/details/gtaspqzglo.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtyktqtyta.html

PHP:  unlink("a.txt");
来源：http://dali.cheryme.top/Article/details/gtmvknwfsv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtokewjplj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtdfdfzdel.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtojgghudg.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtcjahijqh.html

Ruby: File.delete("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtncadtpch.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtidwqnwyd.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gtxnmkqcsn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gterlcsgcj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gtvhinsfwj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtavreqaxi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtmffqdpsd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gtxvuifzfk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkuyulur.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigufen.top/Article/details/gtzutnhufp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtfnytoyuw.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtvnknihnh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gtjjyevjam.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjxhvfqb.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtvdvgfdog.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtsmrilmuo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtegiczbcy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtiuxfmtcx.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gtrevqaygh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gtmadngykn.html


<!-- 参考信息 -->