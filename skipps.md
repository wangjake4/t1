代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gtlvruxjib.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtemrtdycl.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtgnujnvkr.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtucepargn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gtrtczzupp.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtofofoxrf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtgsezcrfy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtrooadeas.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gtfmxyvhao.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gttcrdyxjf.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gtwjrjgimd.html

JS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtrgehijkp.html

TS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtewqumgtg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinghuilouyu.cn/Article/details/gtjclqpcqe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhongyouzk.top/Article/details/gtfcboismw.html

Ruby: arr.uniq
来源：http://dali.smart0.xyz/Article/details/gtlpfppooa.html

C#:   list.Distinct().ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtlohvemnn.html

[D16] 求和与平均值
来源：http://dali.wangshuangyany.cn/Article/details/gtzuokvfsk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gthjekxlcp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gtwojmcpse.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtyvjiekvi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtnnjvvhgw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gtbzwxrhfr.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gtzjbobjwp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gtbpuvxiga.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gtjhspojfo.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gtjenhpvvl.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtgvxlwman.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtzdnqfvuw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.0kj1m.cn/Article/details/gtixtmiqnq.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gtadxrjjhm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yanxiufei.cn/Article/details/gtvlqflyxt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gtdfrtzfyb.html

Ruby: arr.max;  arr.min
来源：http://dali.aizwys.cn/Article/details/gtxgwlbwsw.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gtgttwzkhj.html

[D18] 扁平化嵌套数组
来源：http://dali.dianchejie.cn/Article/details/gtlvlcxjsl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gtrtzgvwwd.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gtksrtzojd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hfpthk.cn/Article/details/gtimdsfzug.html

TS:   nested.flat();
来源：http://dali.shuidangran.top/Article/details/gtwwlhpbjn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtdqjvlmqd.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gtlybmaiaz.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gtylcdkqsd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.svipenyu.cn/Article/details/gteubtjqku.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gtbjkasdeq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gtncamiqni.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.kuanghao11.cn/Article/details/gtcsxzlndc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gtrkbjdtel.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtrukaaamx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuxming.cn/Article/details/gtbhaozbfl.html

Go:   // 手写 map[string][]T
来源：http://dali.hammf.cn/Article/details/gtykpmqiuf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gtursoizpb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aibaodan.cn/Article/details/gtjqnzjhgm.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gtolxfnjil.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gtgoatikku.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtddcirmhv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtksseemog.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtdhfgcyga.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guannengcc.top/Article/details/gtyofrfoxr.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gthifrwptm.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gtawmotqsi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gttrcvmlir.html

[D21] 判断是否包含某元素
来源：http://dali.nanxuanxn.top/Article/details/gtkvmdbuvw.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtfweyvddv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gtgvdcgmzk.html

JS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtlnlhkyox.html

TS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtueglzaic.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtjsnrknez.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gthxbgxouy.html

Ruby: arr.include?(x)
来源：http://dali.birdmap.top/Article/details/gtxnjllknr.html

C#:   list.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtquagdjfe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dianchejie.cn/Article/details/gtgkpslcad.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ydzc1.top/Article/details/gtwszodkcq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cucudq.cn/Article/details/gtikbbzpdn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gtymddmnvs.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gtcchmjvwm.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gtkfmaddtj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yvedp.cn/Article/details/gtcdefxnwg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gtjhogvzej.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gtoriczbjo.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gtlmgqbcmx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gotoacloud.top/Article/details/gtrvgswpnh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.bjfxy.top/Article/details/gtdqahifrs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtctgdemyp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtksmvfycr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgufenzy.top/Article/details/gtefgjpfiz.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtesmuaego.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gttqntpqeh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gtdcpwotol.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gtrbmxnjau.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gthichdinm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gtubwdqgnf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xylfe.cn/Article/details/gtniftbvzc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gteainswhd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gtczgkgmqf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtwcmrnoxi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gtrddhxwmi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shangyingyoupin.top/Article/details/gtduforkab.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfktmcqt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtjzpagazt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.316326.xyz/Article/details/gtsnceznui.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cucudq.cn/Article/details/gtusatbubs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dashuyun.cn/Article/details/gtpaegmlqn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gtiewakqab.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gtjcazkbox.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gtktjjysyq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gtfdxwvzfq.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gtwekdmtks.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtguapldzj.html

PHP:  implode(", ", $arr);
来源：http://dali.zhixingplan.top/Article/details/gtnilypixb.html

JS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gttykjcalr.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtjqaaxhrs.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtcqiidlzf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gtmukuudom.html

Ruby: arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtifseuxve.html

C#:   string.Join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtnhfsiulw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtmpwhyqld.html

E. 字符串处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxpraguc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwrtgoert.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtmlrjtdpa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cashguo.top/Article/details/gtuktallnc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtxyxyxxez.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gtopyovpzq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gtvbrpldpn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdcatvoq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gtzacnubxl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gtzjzkpqgb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pycfn.com/Article/details/gtobktkhfi.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzcixkxw.html

Py:   "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gtzhfjxxgi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gtfvwzbfkk.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtgbzdtajc.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtrunzkdsb.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtagruxabg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhongyouzk.top/Article/details/gtywrmqqqh.html

Ruby: "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gtxkatwtyy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.iojbl.cn/Article/details/gtlwtsjjmq.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtcuodysxd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dashuyun.cn/Article/details/gtpkchusuu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtpcfrytaq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtzctcracv.html

TS:   s.slice(1, 4)
来源：http://dali.yj202588.top/Article/details/gtfblixemm.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtaislmsln.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gttunrgbmb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daxiang520.top/Article/details/gtogwilixq.html

C#:   s.Substring(1, 3)
来源：http://dali.pycfn.com/Article/details/gtnjhygjpy.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gtqtjpdayc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtwnpoipql.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gtouursvxv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gteznkgmkc.html

TS:   s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtrckmkzbx.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtfdixcqel.html

Go:   strings.Index(s, "x")
来源：http://dali.zycfv.cn/Article/details/gtsxuxmgiq.html

Ruby: s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtbtpllekw.html

C#:   s.IndexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtqwconeqk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258.top/Article/details/gtadvuwstd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gtpbynrboq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgufenzy.top/Article/details/gtctvpppjb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtjhsiuqpz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtfmxilwuw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtqnwknyhn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jianghu66.top/Article/details/gttyjwhtkt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtpthmmufg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtevnfdqvc.html

[E06] 替换子串
来源：http://dali.smart0.xyz/Article/details/gtakhhuira.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtoletryxu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangdashe.top/Article/details/gtulcqhsvw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtfomuymod.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gttiwbngfh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtbaqbwqwn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gthdzfbede.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gttwdpdlaj.html

C#:   s.Replace("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtrmjgcwep.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtmnobjltp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cdnleiting.top/Article/details/gtutkpyjbl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtewzatowu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gtlutnzxeb.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gtptbkrati.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gtrhfzyioh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gtfxosfjkf.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gtqznnsanh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgolrqad.html

[E08] 数组按分隔符合并
来源：http://dali.aizwys.cn/Article/details/gteyamyyij.html

Py:   ",".join(items)
来源：http://dali.yj20258.top/Article/details/gtrmhmpwgw.html

PHP:  implode(",", $items);
来源：http://dali.nwbrower.top/Article/details/gtwnnpmkba.html

JS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtyaoomtmz.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtnxdnmsao.html

Java: String.join(",", items)
来源：http://dali.daria6918.cn/Article/details/gtemqyuwkq.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gteafknzst.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtvlfevuoz.html

C#:   string.Join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtoaaipnrb.html

[E09] 去除所有空白字符
来源：http://dali.tianlin.xyz/Article/details/gtjmnltbge.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gtdgteshgu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daxiang520.top/Article/details/gtcnohtmow.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtfujkshoe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtpbcqidkp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtnbrygjlj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daria6918.cn/Article/details/gtwbmacgur.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.iojbl.cn/Article/details/gtycsgxweb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtegvrlcsw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xylfe.cn/Article/details/gtnhecfdsn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtjmkpwywu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gtiynglsxj.html

JS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtbmcppjhu.html

TS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtqgzomqpt.html

Java: String.format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtmyjpaalr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtsiaiayvy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtwitugqba.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gtigcctirf.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gtjmgosiiv.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoijwggww.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gtspphvlrk.html

JS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtouuasbdy.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtkynyfzyr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuxming.cn/Article/details/gttykxjzds.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqxcqfee.html

Ruby: s.reverse
来源：http://dali.wangdashe.top/Article/details/gtgjkopuku.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtmguzquua.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtlqmtqqqe.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gthpgtsyzv.html

PHP:  substr_count($s, "a");
来源：http://dali.daria6918.cn/Article/details/gtvtyzyvkp.html

JS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtffrbfeio.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gtbzccxjfe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gtrbqnhesv.html

Go:   strings.Count(s, "a")
来源：http://dali.zhoulong.xyz/Article/details/gtupjgdtdn.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtdhlmowse.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gthtmlebpx.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwkhsthe.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gtktrotzeg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cashguo.top/Article/details/gtpljleqrq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtwbnjacar.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtvwammuez.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtpubbuebs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gtgvdhaajj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangshuangyany.cn/Article/details/gtictnjqdx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtnuxnybyl.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gtijxuioni.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhongyouzk.top/Article/details/gttynspmpq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gtehkcjfnv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gtchbmnelc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gthhjlziet.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gtooijzwbn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gtrbtxvjoi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwpqtpxu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gtvhsvnvju.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwiqfwmn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sxryk.cn/Article/details/gtzhbmaonm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gtotczbyzg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.haohaochexian.top/Article/details/gthoomictt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgfzy.top/Article/details/gtmxlrqzmr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnxiangtu.top/Article/details/gtyimnuwra.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtcefjrvct.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xziqi.cn/Article/details/gtqzufnwbl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizohvitr.html

[E16] 数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gtnxoopuvo.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegodcidl.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gtmxoiljhm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtpntqdnpb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtkhwdxtgs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gtexcvopqp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtwjjfgpec.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gaohongyu789.top/Article/details/gtzwyqjtlx.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtashwccir.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gtjujqrqhb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gtihvrxcfx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtursjlmrf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuvbvfup.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtkygafevb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gtdyghlipi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gtpmgwumvj.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gtrbevcjry.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hongshengwenyu.top/Article/details/gtirggyzon.html

[E18] 模板占位符替换
来源：http://dali.xuetiantiany.cn/Article/details/gtzcjiaalr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gtweorllvb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gtzucepfih.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtvgksxhpk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gttcajtttj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtxnjlvbcv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtjjfdmhyg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gtzreinapq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cashguo.top/Article/details/gtoyaxenia.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gtzhwmpkye.html

Py:   s.splitlines()
来源：http://dali.jlsjyb.cn/Article/details/gtyjmuldnb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gthegosjou.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtbximrjuq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtguishplg.html

Java: s.lines().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtvfgcfibw.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gttdnpllsn.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gtoavbnmra.html

C#:   s.Split('\n')
来源：http://dali.dashuyun.cn/Article/details/gttfkdsxar.html

[E20] 判断字符串是否为空
来源：http://dali.havefunace.top/Article/details/gtowawoaic.html

Py:   if not s:
来源：http://dali.xylfe.cn/Article/details/gtqlzlbhnt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gtzbmwaytw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gtyepiigmt.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gtaevwgtrk.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrmglgqbv.html

Go:   if s == "" {}
来源：http://dali.zhongyouzk.top/Article/details/gthhhyadnu.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtocfuayse.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.meibo888.top/Article/details/gttdzgared.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gtrsfgyzls.html


<!-- 参考信息 -->