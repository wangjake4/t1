代发 wailian999

[D11] 反转数组
来源：http://dali.c1oappe.top/Article/details/gtzritanro.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gtsdrsqkap.html

PHP:  array_reverse($arr);
来源：http://dali.daxiang520.top/Article/details/gtjncnpjkg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guowangkeji.top/Article/details/gtbbmobqrb.html

TS:   [...arr].reverse();
来源：http://dali.zhengqikj.top/Article/details/gtzeuqvrms.html

Java: Collections.reverse(list);
来源：http://dali.fengsongda.top/Article/details/gtxkfehuwr.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtyeowhaoi.html

Ruby: arr.reverse
来源：http://dali.hysaishi.cn/Article/details/gtokpiacgb.html

C#:   list.Reverse();
来源：http://dali.cucudq.cn/Article/details/gtwlqtjryg.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gtzmmxzvyt.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhvppyut.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenlongwang.top/Article/details/gtjsgpmhqq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gtgqiycceb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtqxeibhcm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gtvogaahkc.html

Go:   slices.Index(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtngbahmbe.html

Ruby: arr.index(x)
来源：http://dali.0kj1m.cn/Article/details/gtwlqjuzcn.html

C#:   list.IndexOf(x);
来源：http://dali.iojbl.cn/Article/details/gtjwlkfsrw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.316326.xyz/Article/details/gtdfcmemdi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gtzrilfydn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtrtyjfosy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtdefcchho.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtkuhkbkbv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gtinvbmwre.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gtejhodmeq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtvzazunjp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtdegshphc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cucudq.cn/Article/details/gtthczlwge.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtdpxasotr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gtjcokfeia.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtstxphlcs.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtmtgfkzuh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuxzgxkv.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtacuzhame.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscorkswn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtaglqcpxo.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtjoyolurv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtytscqemr.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gtrbvhlhyi.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtybfghynu.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrmpffzj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtlgncmjlz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gtxrfpuhpv.html

Ruby: arr.uniq
来源：http://dali.pycfn.com/Article/details/gtsaagtxur.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gtqcvacugi.html

[D16] 求和与平均值
来源：http://dali.smart0.xyz/Article/details/gtjmqhjnba.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gtkqqiebhw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtnkfkpdek.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtmwdvirzc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtabbicxbp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gtwfnvenut.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gtpfmtylty.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aizwys.cn/Article/details/gtqusrrgcz.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gtizmlymkk.html

[D17] 最大值与最小值
来源：http://dali.cheryme.top/Article/details/gtcilbppuj.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtpkuhtudy.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gtiwpxtkvx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xinyue.icu/Article/details/gtpclnlxyj.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gtrzpltbon.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gtkcicebpq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpglmjisr.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gtkpzgxtyx.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoliuxza.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gthdlrxthg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.quarkkingdee.top/Article/details/gtahzmznec.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gtadrjxnvu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gtuyghufra.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gtyrarlwgr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gtcafpxsrh.html

Go:   // 手写双层循环
来源：http://dali.shangyingyoupin.top/Article/details/gteunajyuo.html

Ruby: nested.flatten
来源：http://dali.guowangkeji.top/Article/details/gtddzhukvl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtmfothbjv.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gtqhzmmgsd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gtrgdgpqgs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gtxatnxeih.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gtquqoojbb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gttkfuwlyn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gturfjzwaa.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigfzy.top/Article/details/gtfzvsclrw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gtftqaivxd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jlsjyb.cn/Article/details/gtujkwhgft.html

[D20] 统计每个元素出现次数
来源：http://dali.shzxlz.cn/Article/details/gtdlgnmfep.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gtwkuwhvnw.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtflmxndbt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtnbzbiyzv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtdabnonlr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gtbyhatdet.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gttqrrykgt.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gtgllszxbc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gogol.net.cn/Article/details/gtltmjscrq.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gtgwmlvaxc.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtainqoqpl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbylsldzc.html

JS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtqipngfpc.html

TS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gttpmsuowm.html

Java: list.contains(x)
来源：http://dali.yonumen.top/Article/details/gtwckkbltx.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtmslfvkkg.html

Ruby: arr.include?(x)
来源：http://dali.aibaodan.cn/Article/details/gtbojaakaf.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtzdotyykw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gtqxvqsasr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cashguo.top/Article/details/gtvfqowckl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gtfsjpkuwl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuxming.cn/Article/details/gtejbulrgd.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gtysedomsy.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gtyurvcqfj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnqzz.top/Article/details/gtpkbckhsp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gtyqxybmam.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gtpjlgresb.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gtprznboje.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtubztqput.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtbbzxxhnd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmesisupy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtddwiaehy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hysaishi.cn/Article/details/gtkycltcmg.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gtkdfgjmfw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gtkrqvryhd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gtmngzvtia.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gtaogguedd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gtpjsnxswh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.bjfxy.top/Article/details/gtadmtpnmy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtwlwgwdnb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtvobgwgbi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhoulong.xyz/Article/details/gtdiaqjxaq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxyswarr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nwbrower.top/Article/details/gtctmihptn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gttbfsnimv.html

[D25] Set 集合去重与交并差
来源：http://dali.cashguo.top/Article/details/gtkiqlgjeu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.redwolf501.top/Article/details/gtrrljksht.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtqmfyboqk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gtxdscrccq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gttohernns.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gtzxrmpvzt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jiagoushi.top/Article/details/gtmtbirucg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtydscucie.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ivvv.top/Article/details/gtonjhnqyj.html

[D26] 数组转字符串
来源：http://dali.daxiang520.top/Article/details/gtgevzjvjw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllpoxksx.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gtskkinoba.html

JS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddvpphol.html

TS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtqxvdfcyp.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gtqxhtwxac.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhongyouzk.top/Article/details/gtnkopxctg.html

Ruby: arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtlhnormre.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtmdbfpkwj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkzybelse.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gtjvsdgnby.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthfgcrcku.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtdpinovlq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yongpay.top/Article/details/gtiwvlkwgd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gtoctolcjb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuitsxhxu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gtyfclheaf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gtbsdjfqxn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahlfqric.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gtyrzgwvzf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtikdjnqzv.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gtgbgpzqcj.html

Py:   "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxmovidc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cheryme.top/Article/details/gtvbejmcgr.html

JS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtzpecekam.html

TS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtibbwrwvf.html

Java: "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkiuadfp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gtfxaonkfa.html

Ruby: "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gtlroabiuc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gtufzsrfsg.html

[E03] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtudzvyimh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.316326.xyz/Article/details/gtbwbirpxa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtytsxgskr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtbpvwwbal.html

TS:   s.slice(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtfzujyldx.html

Java: s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtxceswzlw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ppjwa.cn/Article/details/gtytulqejd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.iojbl.cn/Article/details/gtisjqojzy.html

C#:   s.Substring(1, 3)
来源：http://dali.hysaishi.cn/Article/details/gtutspqcaa.html

[E04] 查找子串位置
来源：http://dali.birdmap.top/Article/details/gtcvxjlqeg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gtcwimdiaj.html

PHP:  strpos($s, "x");
来源：http://dali.cucudq.cn/Article/details/gtvrxkhoci.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hfpthk.cn/Article/details/gtwmdvlqjf.html

TS:   s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtvymhfnkv.html

Java: s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtrmywrcvt.html

Go:   strings.Index(s, "x")
来源：http://dali.zhixingplan.top/Article/details/gtqslclksb.html

Ruby: s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtixrmzqpf.html

C#:   s.IndexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtquqjcbrk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gthrpjrmop.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gtatjryrzs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.kuanghao11.cn/Article/details/gtxkpnguip.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gtgkofgvfy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gtnvcafbnk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtjvbxyokh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yvedp.cn/Article/details/gtxxpedluu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ppjwa.cn/Article/details/gtraakoowd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtazcicbiu.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gtrxnoknzq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtcpxsayil.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aibaodan.cn/Article/details/gtrujhxpzl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtoivzsefi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtosrxjryx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtyebztmae.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gtukyulbqn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtmkfwloqt.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtgaarnjlw.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnvbzabr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gtdntfxndd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtgiwxecwa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dashuyun.cn/Article/details/gtvxnghkcc.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gtftowyjcm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yueranfly.top/Article/details/gtriurwvfa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gtzjgbjlmd.html

Ruby: s.split(",");  s.split
来源：http://dali.guowangkeji.top/Article/details/gttwrlnoux.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gtxtnlddhr.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258888.top/Article/details/gtpcppmlxc.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gtcuoskwzr.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gtaudgjxot.html

JS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtjcshidxc.html

TS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtotzlmdur.html

Java: String.join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gtokpsbhuo.html

Go:   strings.Join(items, ",")
来源：http://dali.nwbrower.top/Article/details/gtvadkvqll.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtgobiypec.html

C#:   string.Join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gtndzddjbb.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gtawkgarsj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtrqbdhvot.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gtgxedgdkm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtdodxxtco.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtfuotwzwr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gtwxcpdcqy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gtouhbxbdi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gtefkszstx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtszfhbrxm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.bjfxy.top/Article/details/gtqibbtlxd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzonxpqww.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.svipenyu.cn/Article/details/gturspmzjl.html

JS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtxsqaioza.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtgyicrjrd.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtqbvqowbh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtokquohcq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtmkwtbbfa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gtnupkvzbf.html

[E11] 反转字符串
来源：http://dali.wangdashe.top/Article/details/gtkxgwateq.html

Py:   s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtvpaafbln.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gttkfcrrfj.html

JS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtzqabhvri.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtrzzciijr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gtfgkrijts.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtvarytqer.html

Ruby: s.reverse
来源：http://dali.cashguo.top/Article/details/gtfgomuyvm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtsrxwhjyo.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gtippwhdck.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtziipnvbm.html

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gtqyefpkrf.html

JS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gthjooqpnc.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtsffcecby.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gtsmtuzlcx.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gtsnrsjgxh.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfueqsun.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gthwfcfzup.html

[E13] 逐字符遍历
来源：http://dali.fzhhl.top/Article/details/gtqxndgudm.html

Py:   for ch in s: print(ch)
来源：http://dali.ydzc1.top/Article/details/gtqusaytby.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gtrpwcehyu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtxbebgmep.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtvbprsegh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gttfjbgudu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj202588.top/Article/details/gtcdyfhmub.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gtzbcdahfg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgphdbxvt.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gthnqtgtxo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gtzyellujw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtpqrqqluq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zycfv.cn/Article/details/gtkzryjifv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gtkkuezmwk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtbdqkgcuh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gtfhzwheoy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gtqxpctmjc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxbospwf.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gtrlqtypuz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tianlin.xyz/Article/details/gtgozsyoib.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlqqqhvb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdamzvjuq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fengsongda.top/Article/details/gtzjfnojpj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fengsongda.top/Article/details/gtuttwgxnp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnptwrrrm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gthyjtwgat.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpdzgsnc.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gtxsinihmv.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gtqsfepbli.html

PHP:  number_format(1234567);
来源：http://dali.xinyue.icu/Article/details/gtfcjworvd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtebmrhwwu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtopojaqwf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pycfn.com/Article/details/gtzkctgost.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ybcxt.top/Article/details/gtnaakfqdj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdpmbuvg.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gtjrcxiarn.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gtewwmtdbg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gttznqkpai.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gthqtnuufo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtlulutogc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtgymdixda.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtbdjdwswo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xziqi.cn/Article/details/gtkpiqfyao.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gtydccnwbb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gtxgavycao.html


<!-- 参考信息 -->