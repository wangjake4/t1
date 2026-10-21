代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtroyuvwms.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gtuudccndh.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtuhqvlguw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhoulong.xyz/Article/details/gtcmybhtka.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xylfe.cn/Article/details/gtmfduwcqj.html

[D24] 字典 / Map 基本操作
来源：http://dali.pengpengdd.cyou/Article/details/gtpptdijce.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.snrcjt.cn/Article/details/gtahfzrdni.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gtjqdbfmpo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gtzwkbsgrw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gtcekdyzyg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aizwys.cn/Article/details/gtjwgqihtr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shzxlz.cn/Article/details/gtwvpxrcje.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.mhx1999.top/Article/details/gtunsexcem.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sysykeji.top/Article/details/gtfqxgqwbt.html

[D25] Set 集合去重与交并差
来源：http://dali.gaohongyu789.top/Article/details/gtwytovmjm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtmwhgczlz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtulrjxnfm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuanzhike.top/Article/details/gtotzbxzsj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtmvemfszv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtenfucyxa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcorlntx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gtecntzxwe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkruauief.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gtceylatwk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtjhymlrmv.html

PHP:  implode(", ", $arr);
来源：http://dali.havefunace.top/Article/details/gtlsidbbww.html

JS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtzoapglwz.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtqfbclvja.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtgcrvyogi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gtxnwgmxzh.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtmhgphmiv.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtnetqgrzw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkxftcerh.html

E. 字符串处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdugsojid.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmryjkmrf.html

[E01] 拼接字符串
来源：http://dali.meibo888.top/Article/details/gtxnprvgsu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sxryk.cn/Article/details/gtyfizqdoe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gzhubu.top/Article/details/gtbwnotdvz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtqxfoelpb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtymelucaq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.iojbl.cn/Article/details/gtbdkfjuch.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gtfnmstesq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zycfv.cn/Article/details/gtsegymmyr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtmyxpxjjk.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogknhdzi.html

Py:   "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gtuduafufa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gtkobcrgds.html

JS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtsqjbxyln.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtgtyocbyt.html

Java: "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipvkqqdp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fengsongda.top/Article/details/gtclztivyt.html

Ruby: "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtnqsuoilr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gtatjtbugb.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gtwhowbvtr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gtumunzuzn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtmczimcoi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gttpmttcyi.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtfqqjbmxx.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtnfrbdogd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtnhbtrsxy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangdashe.top/Article/details/gtlewdypkz.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gtkisbpyly.html

[E04] 查找子串位置
来源：http://dali.ppjwa.cn/Article/details/gtyxtkawom.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtggmvcbqe.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gtjkdabhxm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shzxlz.cn/Article/details/gtqrndubjd.html

TS:   s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtcrqnlxzw.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtochkztcj.html

Go:   strings.Index(s, "x")
来源：http://dali.chenjidiqi.icu/Article/details/gtqycpfgpy.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gttpsmalxf.html

C#:   s.IndexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtrwplfjel.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.0kj1m.cn/Article/details/gtrvtuwsdb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtlgaeapzw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.kuanghao11.cn/Article/details/gtghbkagjr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtqkkiecuz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gtlcjrpdbz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtggrdpqqx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gtvnytlvhm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cheryme.top/Article/details/gtijsqptqu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtgtkjtrst.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gtaimimlwh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtkczdddde.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.svipenyu.cn/Article/details/gtkmtkvnbn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtfpmjkhtf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtrfdjgded.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtewumzgyn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gtqzpevfst.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gthqovbwhk.html

C#:   s.Replace("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtfbbjrvct.html

[E07] 按分隔符拆分
来源：http://dali.dianchejie.cn/Article/details/gtwocvwwmc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gogol.net.cn/Article/details/gtgkboepji.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtlhfiupoi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutrctfmb.html

TS:   s.split(",")
来源：http://dali.kuanghao11.cn/Article/details/gthbovypmw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhoulong.xyz/Article/details/gtodffzxoa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gtxjhlgdao.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gtxkqapzyg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.haohaochexian.top/Article/details/gtuzhghqsw.html

[E08] 数组按分隔符合并
来源：http://dali.yuxming.cn/Article/details/gtiaghbgjf.html

Py:   ",".join(items)
来源：http://dali.chenzaomai.com/Article/details/gtqotmtxsm.html

PHP:  implode(",", $items);
来源：http://dali.hywenlv.cn/Article/details/gtdwiaezuz.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtmsdtoqgj.html

TS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtyybsofip.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gtyewmgzfj.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gtriprkboa.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtnuydkmkm.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gtzlwdtiiy.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gtwsxytggy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gthcgeqzbv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxinkj.top/Article/details/gtmriljiub.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtsmoapxfc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtnqulapgr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtnlogtcdl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.c1oappe.top/Article/details/gtwqojrwus.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gtpuvkqxuy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwoelikmv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cashguo.top/Article/details/gtlvmasnag.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtbqxlrqql.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gtqmhrpgoy.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtmomeccdm.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtwgkxymgv.html

Java: String.format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbhirsuh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtqaptajjt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtuubynkho.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gtwqxhrute.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gtubtsaknd.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtrkrvewpe.html

PHP:  strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtjaqqxyab.html

JS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtqpwcgarh.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtmfvaeuki.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtvmfaehep.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gtdqecazoh.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtkqqebufp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gttnifkglp.html

[E12] 统计某字符出现次数
来源：http://dali.cdnleiting.top/Article/details/gtgqynnxsa.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtlgmmjjxt.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gtmdghkbxg.html

JS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtsthtwrze.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtfwotftep.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gtmqbyktuk.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gtqqjxfnzu.html

Ruby: s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtrcsxopmb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gtrbcwgkix.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gtyzdkxzth.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gtwlcyrbvs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yangfankeji.com/Article/details/gtnrobhnyy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gteiebrdfh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtxlcdynkf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtomphjarb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gtnspenhqd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gtnibhschh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.smart0.xyz/Article/details/gtrucgrkpm.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gtimwrkqyk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gthqbicjxi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dianchejie.cn/Article/details/gtiebpwlxi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhiwuduotai.top/Article/details/gtrriilbzv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gtmkeeyvqh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtpvxmnsyn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuanzx.com/Article/details/gtgklcytvr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.quarkkingdee.top/Article/details/gtiyejnycw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycaxadku.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gtldblwzjy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gtcqkruhca.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gtfuvafpnb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gzhubu.top/Article/details/gtfpdoxcrb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gtikhcemlg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gtaszzkwhr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gtucyzmrfs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.birdmap.top/Article/details/gtvvaszqrj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gttmyvjjha.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gtdfknzovl.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gtohtoawsv.html

PHP:  number_format(1234567);
来源：http://dali.hysaishi.cn/Article/details/gtsodttibr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtgmarqzii.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtgwcwxits.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwainicnv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtduyciyek.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258.top/Article/details/gtbltvqatd.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gtxmtcxjow.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gtbivsyjhe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gtacvwmxty.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gtcnriomna.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gttrtlrknz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtaxyobtpn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jianghu66.top/Article/details/gtlwtbuqne.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtdggywtsm.html

Ruby: s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gtbkvkhsuq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gaohongyu789.top/Article/details/gtdxslwyvt.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gtqvbnhqdm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsplpjalq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gtqdchhlew.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gttaegvxfs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtodhxlvqx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtyfuyqpap.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gtwngnosae.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdsjggdz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigufen.top/Article/details/gttzpjfgxa.html

[E19] 多行文本按行拆分
来源：http://dali.jyoumei.cn/Article/details/gtriexpwgr.html

Py:   s.splitlines()
来源：http://dali.gzhubu.top/Article/details/gtqksuwktd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sysykeji.top/Article/details/gtnqcsdsyn.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gtpatoaqcs.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtdbparera.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gtxkhfpddz.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtrmrujzre.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gtgsnwqktl.html

C#:   s.Split('\n')
来源：http://dali.jinqigfzy.top/Article/details/gtmlpdmmdc.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gtogqmsvdm.html

Py:   if not s:
来源：http://dali.pycfn.com/Article/details/gttrdxjlxk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gtsnhvjtto.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfzlnvbcg.html

TS:   if (s === "") {}
来源：http://dali.havefunace.top/Article/details/gtiayxerao.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtmleucrpg.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtcoriiplu.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gtxgctqsew.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtbpfzwcsv.html

[E21] 超长截断加省略号
来源：http://dali.yongpay.top/Article/details/gtrrcvozgp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gtzvqbbqzj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gthfulpogy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtaswdvysc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtaatrfxlf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtxmpdggkg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gtrklqvfky.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtsofetbck.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtnesladdl.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gtdomipcch.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuxipojy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtgqnkilze.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtoiopvchc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gtrjmikbud.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gtkotpmfjt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gtqgxcoekv.html

Ruby: s.bytesize;  s.length
来源：http://dali.iojbl.cn/Article/details/gtflalfmsp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yueranfly.top/Article/details/gtwgusgrmo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtsigxlowg.html

F. 文件与目录
来源：http://dali.pycfn.com/Article/details/gtjcygmvyi.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtciesyfjv.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtleruurjb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtbygwhpbt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtzngfntbe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gttsjbipxt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtixthsxle.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtwgtmprtu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yvedp.cn/Article/details/gtdouapuoi.html

Ruby: File.read("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtcqumuxhp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtqvebvdym.html

[F02] 逐行读取文件
来源：http://dali.jianghu66.top/Article/details/gtbmmaryqx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cdnleiting.top/Article/details/gtstpnuxez.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzcgfuium.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtopoeqphb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtbsxaomtc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfiysfvdv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtzxjxsjro.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gtfhviegss.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gtexueayou.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gtlqzqmatc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gtxodoqfuv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtyaghzvlh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtuurwrclt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtirspfzaf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gtshtfcitz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xziqi.cn/Article/details/gtoxdkcrfx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gtbjdeiywv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtvwprczub.html

[F04] 追加写入文件
来源：http://dali.gotoacloud.top/Article/details/gtpiwgdzee.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gthcscfoww.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gtavwtizwg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtxwmiudmu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtowelqxic.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtrpgcxvox.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gtoamwgzgr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gtqwfgzyxn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtmmvhxppb.html

[F05] 判断文件或目录是否存在
来源：http://dali.pycfn.com/Article/details/gtpbkcskeo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gtdsfbeqxd.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtbezbgduw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtkxoyjiqo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtgljhakfx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtyfecmpmk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aibaodan.cn/Article/details/gtuahnjjpk.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtwxkkhwbw.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gthoovejni.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtahajjkpt.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtnjazxoba.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gttxndhztl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtvhrqgidv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtclxdqsvc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtyfoiffkz.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtamwlnwnv.html

Ruby: File.delete("a.txt")
来源：http://dali.havefunace.top/Article/details/gtunmayrpg.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gtfxvldegr.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gtgftlllmi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gtzgsmvfqs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtkfqgvfmr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtcibaglig.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtkhvwpcop.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gtjojkahna.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gtqxdsyluu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gtdvnxiibr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtgvtlzyna.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gtcffncgux.html


<!-- 参考信息 -->