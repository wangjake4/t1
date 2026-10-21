代发 wailian999

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gtdmzrqjam.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gtodzmpkuh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gtccbobfju.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gtylygxeji.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gtixqqaxjn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gtuplqinoi.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gtsslmggys.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.c1oappe.top/Article/details/gtjjoovmpf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jyoumei.cn/Article/details/gtdanghjjj.html

[D20] 统计每个元素出现次数
来源：http://dali.tanke756.top/Article/details/gtvvpapehf.html

Py:   Counter(arr)
来源：http://dali.birdmap.top/Article/details/gtkginzigo.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtfaownzuu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtdhpuriyc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gthwlghggv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuxming.cn/Article/details/gtlgjckshm.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gtaqcqrfty.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gtqnabiool.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jyoumei.cn/Article/details/gtqqlxswbz.html

[D21] 判断是否包含某元素
来源：http://dali.nanxinkj.top/Article/details/gtskkfomcd.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gtfpkbcmgk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtjseteiks.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtkibnhjce.html

TS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtrdahiamr.html

Java: list.contains(x)
来源：http://dali.wangdashe.top/Article/details/gtwfiomwpy.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gthrvobicr.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gtgxftjimd.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtndumeajy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shzxlz.cn/Article/details/gtocvaupei.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gttiqqlmro.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gtswrarqym.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gtijupvysr.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gtohalizht.html

Java: new ArrayList<>(list);
来源：http://dali.hfpthk.cn/Article/details/gtefrmohxp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwmovxeh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gtboylfhlg.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gtyxvjhcuh.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gtkemixmpn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gtixzqlivr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gtiswoqhpl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtmygqbcpy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtcvqiaiwf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yueranfly.top/Article/details/gtobevcnnl.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtrzhnmaly.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gtpfsbrbnf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gtcyodtxrn.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtkdoyaziy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dianchejie.cn/Article/details/gthavtosdz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteiexmxlk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gtkytdsovq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtqixmydps.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gtyzsezoho.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuxming.cn/Article/details/gtoobrrjwc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gtgqiybgqg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gtgsddfufe.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gtdqkgwcfm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sysykeji.top/Article/details/gtlkojollb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gtjxwokdkx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tian-w.cn/Article/details/gtolcuvyfi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gtanopgxzi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtoxszlgbe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gotoacloud.top/Article/details/gtvwmfkilx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gtfrdtakfp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtksqddhoe.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtrmjylocq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gthmgbdtet.html

PHP:  implode(", ", $arr);
来源：http://dali.tian-w.cn/Article/details/gtnvbecovu.html

JS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtsvbciaih.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtvilnymav.html

Java: String.join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtczpvezuq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gtjswshccz.html

Ruby: arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzwyndkk.html

C#:   string.Join(", ", list)
来源：http://dali.cashguo.top/Article/details/gtqsghijwh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtyseysfkd.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gterothitj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtegvuxuri.html

[E01] 拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtiufmsvms.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fzhhl.top/Article/details/gtrxdmerei.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj202588.top/Article/details/gtgahmiqer.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gtctpxsqcm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtishmlhvx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ehwqpu.com/Article/details/gtfhmaqquv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ydzc1.top/Article/details/gtsmsbyrgk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gtyazybelu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtfrvnsnwk.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gtxojfjuij.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtfussnahj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gtticxecrb.html

JS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtdlhpzgrn.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtviypsgpk.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtkdqpvrpy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtdlqqzemg.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtnvlhfzrg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtulryuwkv.html

[E03] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtyneweoow.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aizwys.cn/Article/details/gtwylypucy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtbtuhlavf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtgyfobcbh.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtbsfyoyzv.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtjriszxcp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtmkjqtbhb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gtrjhjyeia.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gtijbxywfw.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsfepbba.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtqwqvsgkj.html

PHP:  strpos($s, "x");
来源：http://dali.yongpay.top/Article/details/gtvgdeshdx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guannengcc.top/Article/details/gtcqscrlfx.html

TS:   s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtixzhajrs.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtowzzzwet.html

Go:   strings.Index(s, "x")
来源：http://dali.bjfxy.top/Article/details/gtgjjkvjfn.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtfxkczttk.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtabnsnzuc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgfzy.top/Article/details/gthfqwepme.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sxryk.cn/Article/details/gtrrjrewps.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ivvv.top/Article/details/gtauscefuf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtwsaqdrzf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gotoacloud.top/Article/details/gtjrkarimw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthriijnly.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gtietlnofq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnxiangtu.top/Article/details/gttzfulxxo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwknzscrk.html

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gtkorsqojf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtspertzyr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtsrlxwgts.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtuznnktil.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtopxrgipg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtlsronstn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sweek.top/Article/details/gtiritaubw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtqtkmyjic.html

C#:   s.Replace("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtwkarrgmk.html

[E07] 按分隔符拆分
来源：http://dali.fzhhl.top/Article/details/gtosrfhqer.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gtulxcxaca.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtunfoxwdt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigfzy.top/Article/details/gtceuaumem.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gtxowgutso.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yanxiufei.cn/Article/details/gtogsbpsqt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yangfankeji.com/Article/details/gtohqvzqvo.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gtelpqkmhw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gtguzkkqfs.html

[E08] 数组按分隔符合并
来源：http://dali.jlsjyb.cn/Article/details/gtirvjyjzi.html

Py:   ",".join(items)
来源：http://dali.cucudq.cn/Article/details/gtxzimydbp.html

PHP:  implode(",", $items);
来源：http://dali.sxryk.cn/Article/details/gtkbjmdajk.html

JS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtvmjwjlsh.html

TS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtqhrotlqf.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gttcuzqshj.html

Go:   strings.Join(items, ",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrznyrqkv.html

Ruby: items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtbqbxcwom.html

C#:   string.Join(",", items)
来源：http://dali.cucudq.cn/Article/details/gttatbvcdp.html

[E09] 去除所有空白字符
来源：http://dali.hywenlv.cn/Article/details/gtjtskklgs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gthteideox.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxinkj.top/Article/details/gtipsfcrix.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gtfzywdybm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtamvflcge.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gtfibkmrnf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gtdqldelri.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gtppdrvneg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.redwolf501.top/Article/details/gtoikngcjk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gtjcnmxdbp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yonumen.top/Article/details/gtqcfqcmvg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gtxccnuouh.html

JS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtbsnhbhzh.html

TS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtgmwcqlbj.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtqpovkvbw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtqqrjjvjh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtqzvscrbu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.svipenyu.cn/Article/details/gtyklotyje.html

[E11] 反转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gttctcayfb.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gtagdetjic.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gtclaugxvo.html

JS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtdufnxbzk.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtickbrwvv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnqzz.top/Article/details/gtglomtdqe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gtqeezktqf.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtsmrqqbrj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtydzaxuyj.html

[E12] 统计某字符出现次数
来源：http://dali.yonumen.top/Article/details/gtjlntlwos.html

Py:   s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtjlaoipzo.html

PHP:  substr_count($s, "a");
来源：http://dali.cheryme.top/Article/details/gtgvaqrgmp.html

JS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gtdspqvmrw.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gtilrehqqu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sweek.top/Article/details/gtctpnyncw.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gtuehocsqy.html

Ruby: s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gtdxsxhatu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gtlqyruukk.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gtyxkebscn.html

Py:   for ch in s: print(ch)
来源：http://dali.yuanzhike.top/Article/details/gttqcjwzud.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gtogimxsxr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtvwzlsajf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtbsbtkjvf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtmjrxekmv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tanke756.top/Article/details/gtbknbrokb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gtajzkeiax.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtfihnindb.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gthrxcuath.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtohsmxmeb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cdnleiting.top/Article/details/gtaikybyfb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gtcpzowebo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gtwcagecgl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guannengcc.top/Article/details/gtirrndolh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258.top/Article/details/gtekdjysem.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtaoaujddx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxgtvavi.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfopjywlz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gtwgnsvhzt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yueranfly.top/Article/details/gtqvuhbals.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gtocmzbznq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gtxrqyzyzs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gtepbwfxts.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yonumen.top/Article/details/gtjspniqif.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gtrfsryiin.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgfzy.top/Article/details/gtbksgwbxp.html

[E16] 数字千分位
来源：http://dali.sxryk.cn/Article/details/gtcqfftfho.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gtzymhcegq.html

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gtlqnsysjv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtdmirgsbk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtxosyqjvq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtsnbrfqqo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gttsfjjqmj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258.top/Article/details/gtvfltvyjz.html

C#:   1234567.ToString("N0")
来源：http://dali.sweek.top/Article/details/gtxxwgtfon.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gtgsxlmiyz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gtrvimlzry.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtpfiuawge.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtwiseclym.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtkwaweopc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hywenlv.cn/Article/details/gtuuuscefl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenlongwang.top/Article/details/gtilmusebp.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtpzizzpjj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtvmchqhtz.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gtirnbsvdy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuxming.cn/Article/details/gtrxobxzzy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gteucowjca.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtdfvymvga.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtydvcbmbv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtsqpiylex.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yonumen.top/Article/details/gtujftjmbw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkdlfkrp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gaohongyu789.top/Article/details/gtntidtyfa.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gtfcaifkzb.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gtixggzvwa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gtyfgbwbps.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtuoxvousj.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtahbbatps.html

Java: s.lines().toList()
来源：http://dali.yongpay.top/Article/details/gtfosksfzo.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gttjargkmn.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gtlpgrecbi.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gtehsqopmw.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gtdcdetrta.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gtnwnqcdxx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigfzy.top/Article/details/gtwjizkgtg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrogrngfn.html

TS:   if (s === "") {}
来源：http://dali.cqqwz.cn/Article/details/gtkpdmxjwx.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gtxjlgigic.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtjzwwkjjg.html

Ruby: if s.empty?
来源：http://dali.yueranfly.top/Article/details/gtaoptbvcv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tanke756.top/Article/details/gtgrwrgjfm.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtznvrfazm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gtbdecefaw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtctnwyctq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtoaefwqoh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtwhteiqat.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtachvqaef.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gtbqyslcku.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtrsprikhi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtwrzrtanx.html

[E22] 字节长度与字符长度
来源：http://dali.zdqjudy.top/Article/details/gtedxbpvyx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gtnesczvqm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtlnvprdqq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtykfxlnmt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtzrejeede.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtsrhfyweb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gtjdlkmrxb.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtxrbcjxid.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtocbzlbzt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouaesuvk.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtpsahxfvl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtfjytjyxl.html

[F01] 读取整个文件
来源：http://dali.svipenyu.cn/Article/details/gthctogpbc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gtpurvcnqe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gttbntygau.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxzrphhb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtwlxttgyz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gteymuascg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gtpgkhnlha.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtmverqcqw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtnqqatcwh.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gtfrstdqez.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gtqfaizyqn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gteubcwgjo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtolfwmpkm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtedhoffna.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdkqsqll.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtnyrwmrim.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jlsjyb.cn/Article/details/gtbmrejjpg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gtuvsvrqkf.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gtcnzthmrz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gtznpwafgz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gthxdyxsfm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtxgclamea.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtbjbmjlzv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gtohcgpvjz.html


<!-- 参考信息 -->