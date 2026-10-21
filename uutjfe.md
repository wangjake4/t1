代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtnmwtknpr.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gtzvtrnuau.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtcbynuwpm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shuidangran.top/Article/details/gtaygnubiy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gtbqusnuwb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gtuyberwnj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gtelpxsufo.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gtvgkvkomg.html

Java: new ArrayList<>(list);
来源：http://dali.yueranfly.top/Article/details/gtoawctkiw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gtkuurfolk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gtdcunvsnw.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gtverpsula.html

[D23] reduce 累积计算
来源：http://dali.ehwqpu.com/Article/details/gtasxhvdto.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jianghu66.top/Article/details/gtgqnvlgts.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shuidangran.top/Article/details/gtaobzjhhe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtegnmccfi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtkwwqdoes.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gtqbbdeusc.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtwiinwdbq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gtuolofrof.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcrmeeil.html

[D24] 字典 / Map 基本操作
来源：http://dali.yangfankeji.com/Article/details/gtjhajxdqa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gtcfbfkbuw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gttruneqoc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.iojbl.cn/Article/details/gtysatpzgx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtowwephzi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gtmmqnhjmd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.snrcjt.cn/Article/details/gtbuknhtra.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gtdpgzwtyq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xziqi.cn/Article/details/gtvdlwlcja.html

[D25] Set 集合去重与交并差
来源：http://dali.vqdsnc.cn/Article/details/gtanjlwbbs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gtjludmqww.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fzhhl.top/Article/details/gtctkrhynt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtdsicwvyo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnqzz.top/Article/details/gttjhfdamm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gtdxwmebdy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gtvytakwjc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.smart0.xyz/Article/details/gtslbmykak.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gtgrdsbxqi.html

[D26] 数组转字符串
来源：http://dali.sysykeji.top/Article/details/gtjowhtcrq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fengsongda.top/Article/details/gtxfqnmbeq.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtumrvjfww.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtbejczoqv.html

TS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtqdrxvbtg.html

Java: String.join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtkklekrkz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gtyawvjgfm.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtrzpmyxip.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtyeqlefzu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtxoakbwij.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gtcaapximn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkswjeeoz.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtwyoiayif.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gotoacloud.top/Article/details/gtvhzpaigo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnxiangtu.top/Article/details/gtonjkemqs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtbllofvke.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gthlpvprnr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cucudq.cn/Article/details/gtjbvnxurn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yanxiufei.cn/Article/details/gtmbmtzguh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gtlhogtzkc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtetavnzto.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gtoloaxddx.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqtsmftc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258888.top/Article/details/gtjryreggk.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtxqdjrujf.html

TS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtpqxvdrmg.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gticobdguk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.0kj1m.cn/Article/details/gtniqwyphc.html

Ruby: "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gtyartaqgq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjjzueps.html

[E03] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gtjruhtbnh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgufenzy.top/Article/details/gtktsuwxdt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtgaqoxxnr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gtuzwaszdb.html

TS:   s.slice(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtwuivhaxv.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtkbhxcqrt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.svipenyu.cn/Article/details/gtyglsfvfl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtlayinawi.html

C#:   s.Substring(1, 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtnwetjvne.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gtjxtnfvrg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtqubtjnmn.html

PHP:  strpos($s, "x");
来源：http://dali.daria6918.cn/Article/details/gtjrabjteo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj202588.top/Article/details/gtihuljelg.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwvszybq.html

Java: s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtqttcdsww.html

Go:   strings.Index(s, "x")
来源：http://dali.bjfxy.top/Article/details/gtqvvyzwlh.html

Ruby: s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtkjecsiko.html

C#:   s.IndexOf("x")
来源：http://dali.havefunace.top/Article/details/gthrugfkaz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shuidangran.top/Article/details/gtarzucjxx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gtxqanpfvf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ivvv.top/Article/details/gtnuktvyxn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtsfjqhfax.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shuidangran.top/Article/details/gtpmecrkvm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtfthyhgfz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gtdjlswmxz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.c1oappe.top/Article/details/gttiemvody.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtsktilquy.html

[E06] 替换子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjidriscw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtfmldfbra.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cheryme.top/Article/details/gtwfpopapu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtxxsofzac.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtczfknevl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gttyilpmvb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtdekzzdpp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtbyuehiqr.html

C#:   s.Replace("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtdoowgwca.html

[E07] 按分隔符拆分
来源：http://dali.yvedp.cn/Article/details/gtgnvculzj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ppjwa.cn/Article/details/gtfjxwdrrh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtwscdgkqv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aibaodan.cn/Article/details/gtkwldoyeq.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmjzrmdg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sysykeji.top/Article/details/gtixjyeytk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gtirycexfh.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gtkaipcoea.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yonumen.top/Article/details/gtranwscqq.html

[E08] 数组按分隔符合并
来源：http://dali.svipenyu.cn/Article/details/gtmybdmeyn.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gtsyfhfosb.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtyejxqxid.html

JS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtbcdavjdn.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtadbouhwu.html

Java: String.join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtbtifgllk.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gtpmhevefg.html

Ruby: items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtovvokeil.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtyaqenoab.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gtlbczmxxl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gthroxpdwo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtriitrznw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gtgfmgmsqg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtfvhqyera.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtkqgxkkbf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cheryme.top/Article/details/gthjrwfpoh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.kuanghao11.cn/Article/details/gtktemkkag.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gtdnucllik.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gtgxkigamz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtsvmmjrjs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuanzx.com/Article/details/gttdohvlnw.html

JS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtalwguinv.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfoijubfx.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtehtcztbv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtypialivg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtdsjzyevb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gtbyurhwhl.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gtsxjypbrj.html

Py:   s[::-1]
来源：http://dali.zycfv.cn/Article/details/gthkbuyutj.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtdbriwpfh.html

JS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtpextfuuf.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhahtwew.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gtiliqaldi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtnwejcsnp.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gtukztpqyu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gttimnmbhx.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtloizgftg.html

Py:   s.count("a")
来源：http://dali.cashguo.top/Article/details/gtgefgfntx.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gthcexgrwo.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtxcjwuwig.html

TS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtkxtwvdcj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxyiiwtg.html

Go:   strings.Count(s, "a")
来源：http://dali.svipenyu.cn/Article/details/gttkxbfsty.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtqjqhodys.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnqzz.top/Article/details/gtyfeddweh.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gtdhemxkqi.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gtkbksvfll.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gtaseaulnc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtouuidfze.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtyphpdjqs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guannengcc.top/Article/details/gtkjfnsrgi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbyytqtb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gtvfcjtpas.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxplzyxb.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwvrzibl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.iojbl.cn/Article/details/gtlxvhjrpi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtynwzsuyu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gtyobnjgtc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gtnpdrhyur.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gttguxlagt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gtadgdfebs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtepqulyem.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtyggvitih.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtulgiicmw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangdashe.top/Article/details/gttviadskk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gtjtdmadmv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gtvzlofksy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jlsjyb.cn/Article/details/gtmjymyjvj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtimktcfrd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cheryme.top/Article/details/gtclfsdkzp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gtbecnguxw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gtsapjbecc.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gtgicdugbr.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gtdstejpll.html

PHP:  number_format(1234567);
来源：http://dali.zycfv.cn/Article/details/gtshnziucf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtbnlyfbnx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtztglrjoe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtuueajyhl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmeshlav.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.9152youxi.cn/Article/details/gtfynokicn.html

C#:   1234567.ToString("N0")
来源：http://dali.sufxvd.cn/Article/details/gtstgngrpn.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gtbwfxoaey.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gtjsdlvqgv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtcqibfrhf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtvhwxnhoy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gtkdjexnbx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gtlshbwcgd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gtlyiaubdi.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gttdtvitgx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fzhhl.top/Article/details/gtrzmrvhoq.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gthmyxlwud.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlqrpwdv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dashuyun.cn/Article/details/gtmwychtlb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtjoyamgfr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gthrzxfipa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtxstpyxts.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtdhegjrkq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gtithmxhqk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fzhhl.top/Article/details/gttdwoydrb.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gtihefkoha.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gtkbwmouhv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtnxohljco.html

JS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtmnubmipq.html

TS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gthjeltipj.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gtzmgfxvlg.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gtpysobgko.html

Ruby: s.lines
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkzdmaha.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtkmtweuxd.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gtqqinkirz.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gtvgxhxzuh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gtwsjljptq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gtwkhlixoz.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gtrkmoazfu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsairrpxf.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gtnssshtax.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gtlebdhvgw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtnhzhtiux.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gtjoepkbvb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.316326.xyz/Article/details/gtsygfzoif.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gteentmaqp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtjjjydyhg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtqwiuhfem.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtmeinkwgd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tanke756.top/Article/details/gtovrulrpo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gttaibfhxn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtpfjjogwr.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfyyanlb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gtejymyypj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtexopbort.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtcurpewik.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtfywmrwlc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtzimzytwi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtdswuljae.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gtnoykzsqw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gtijxnqmzg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbtnmuiub.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gtjsscywel.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcqzpbti.html

[F01] 读取整个文件
来源：http://dali.xuanzx.com/Article/details/gttfljvbzd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gtmhvrqtjf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtanqakhux.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gtlbdqkxzi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtsvizjjdg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtmlczojeu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gtaafgmipx.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtxdccrwgw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtboclsvrf.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gtopmrvmke.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gtlyrrhyjm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shzxlz.cn/Article/details/gtkhloiokk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtclwjxxwd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtgrqyvmqy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtmnscwxpr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gtdxnirkpd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtnmebhuqf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozijivdj.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gtkogmuivt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtzwapacru.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gthxcsfqvf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtpezqlasv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtrpsjonqw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.smart0.xyz/Article/details/gtyypxxqqb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gtuzlzoctd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gtwoofjoek.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gthnfslszq.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gtbvpyewmp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtywqxdkhl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gtxxoyauip.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuezmyide.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtirfhlnty.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gtioolszar.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gtgobibwaz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jlsjyb.cn/Article/details/gtnhypdztv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gtxjcoekjc.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gtrshzopjo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gtjxaaqccs.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gthwccorlk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtzfcwroxa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtcoyrpulv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtjclllmef.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gtosnawefc.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtrjsbtvmm.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gthgywmixq.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gtrtjikejw.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtvvufnswj.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtsfxyxfld.html


<!-- 参考信息 -->