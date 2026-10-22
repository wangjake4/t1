代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtevmwblny.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gtuivnvyqs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hysaishi.cn/Article/details/gtboynaeac.html

Go:   slices.Index(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtkhiblwsg.html

Ruby: arr.index(x)
来源：http://dali.gotoacloud.top/Article/details/gtqmcnylto.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtgfrumhby.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhongyouzk.top/Article/details/gtaxhsodsx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.c1oappe.top/Article/details/gtyrzjetub.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gtoewkkqog.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gttmpeajmv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gttxnfekvc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gtjzclzarq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.andypj.xyz/Article/details/gtnnhmuxsx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ybcxt.top/Article/details/gtcdcizvpo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtufimwnxk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gaohongyu789.top/Article/details/gtrpadydre.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sxryk.cn/Article/details/gtetfkpsxo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtwbuysend.html

JS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtvuwjawos.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtlzvxdryr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.smart0.xyz/Article/details/gtnuakfbnf.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtuvifzdoj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoziwpzln.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtzkciwwao.html

[D15] 去重
来源：http://dali.gotoacloud.top/Article/details/gthlpxfijb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gtjqxpwaad.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtkpenrhwt.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtacuvuvuq.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtpzpnnnql.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gtjcanprzk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gtljfyubyq.html

Ruby: arr.uniq
来源：http://dali.tanke756.top/Article/details/gtkzjonmeb.html

C#:   list.Distinct().ToList()
来源：http://dali.aibaodan.cn/Article/details/gtksgvvubi.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gtfwnzrhez.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtvyhpgtbr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sysykeji.top/Article/details/gtjujbbovl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtthqgnywr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtjqxbihvb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gtmjupsamp.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gtfuvmeneb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gtugtfovtp.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbfvkcwa.html

[D17] 最大值与最小值
来源：http://dali.wangshuangyany.cn/Article/details/gtdbmumrgy.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gtcwmmeuts.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gtyjmuboft.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hysaishi.cn/Article/details/gtrjuocnpo.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gtpmdeqwxw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gtdzlsyrfp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gtxkraiuqt.html

Ruby: arr.max;  arr.min
来源：http://dali.jyoumei.cn/Article/details/gtksxvkbvy.html

C#:   list.Max();  list.Min()
来源：http://dali.zhongyouzk.top/Article/details/gtchntfonb.html

[D18] 扁平化嵌套数组
来源：http://dali.gaohongyu789.top/Article/details/gtyzqrzeck.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gtbfbbwzcq.html

PHP:  array_merge(...$nested);
来源：http://dali.hnxiangtu.top/Article/details/gtxcdtnbwb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gtezscdryy.html

TS:   nested.flat();
来源：http://dali.ydzc1.top/Article/details/gttcmeqknj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gtmerwjepj.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gtestjkjuw.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gtrjbiehwl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gttlecbywx.html

[D19] 按字段分组
来源：http://dali.cashguo.top/Article/details/gtewonuqef.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258888.top/Article/details/gtsxhkxetx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gtcedsegto.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gtczgygwmw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gtdtkvbjyi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gtvdpthipo.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxuanxn.top/Article/details/gtducdeeyr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daria6918.cn/Article/details/gtyguueumy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dashuyun.cn/Article/details/gtzyuagxiw.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gtpbjrkoio.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gtedreoxea.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptnfbpxc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtmblixztj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gtkrazcemn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gtkodjspps.html

Go:   // 手写 map[T]int
来源：http://dali.nanxuanxn.top/Article/details/gtxeojenif.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gtrwzyheaq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwignnny.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkdjdmds.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gtneitbeqt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gtvesumfgv.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gteathzpji.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtwglcthmd.html

Java: list.contains(x)
来源：http://dali.birdmap.top/Article/details/gtvlrwezjy.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtkqffikku.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gtdiodcsmf.html

C#:   list.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtseltakfy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aizwys.cn/Article/details/gtdutmsktd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ppjwa.cn/Article/details/gturcqpxcf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gtawxcxyhj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gtioyrpies.html

TS:   [...arr];
来源：http://dali.jinghuilouyu.cn/Article/details/gtydhnsnht.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gtbtxpjjwt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtddeitipo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gtxqoqozrz.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gtohmrmpxj.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gtsjjrwdvr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gtjrxghljy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gtzbhkcxsq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtdtbkgdtj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtrgcailxx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxinkj.top/Article/details/gtknvftnqa.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtaaoonoru.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gtyjrhrmjn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.9152youxi.cn/Article/details/gtlckjogit.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gthurfbvyr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daria6918.cn/Article/details/gtafabrwzd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gaohongyu789.top/Article/details/gtmoyapenk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gtdbrkflix.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fengsongda.top/Article/details/gttbqubify.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gtdrnnllya.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtmwvoxllo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gtzxpctlcf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xziqi.cn/Article/details/gtxxjchtxq.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxuanxn.top/Article/details/gtbngwopdy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yongpay.top/Article/details/gtghhlxiie.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gtcoothmah.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnxiangtu.top/Article/details/gtzpmahwir.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gttspsmzmz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gtxlhbnnki.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gtzdinckiq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gtejehacpq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtrygyxowi.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtihflkmlc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gtidnodzli.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtwdhkysgv.html

JS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtswhdyhai.html

TS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gttskxaxxq.html

Java: String.join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhbtzjmj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.vqdsnc.cn/Article/details/gtteaszhav.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtdaspbyhq.html

C#:   string.Join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtdsnwdzdg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtxebsikkm.html

E. 字符串处理
来源：http://dali.dashuyun.cn/Article/details/gtqbnmhxef.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbzjxqsej.html

[E01] 拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtlwytjvkp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gtzjgyqgdd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gtkgalrirj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtfixzwyah.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gtlodcyjvz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gtvmfofite.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gtyyctedrh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gtakyskyjd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtohwnhkcm.html

[E02] 重复字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuirqked.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtqpyjofxb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yvedp.cn/Article/details/gturscspru.html

JS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtnrdrxhor.html

TS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpiyvnbwg.html

Java: "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtlwvmbayh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gtppwjvylp.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtotyqqyba.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gtqotyamld.html

[E03] 截取子串
来源：http://dali.cucudq.cn/Article/details/gthgckdoas.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxfwhcye.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtcpndnoip.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtpkincosj.html

TS:   s.slice(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtjbdzlxmp.html

Java: s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtcaqdvqte.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.meibo888.top/Article/details/gtdgpivyre.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jyoumei.cn/Article/details/gtonnigjfk.html

C#:   s.Substring(1, 3)
来源：http://dali.316326.xyz/Article/details/gtwgagdyzr.html

[E04] 查找子串位置
来源：http://dali.smart0.xyz/Article/details/gtgiybpfsa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gtckzdions.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gttetweafg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gtgmmfcoze.html

TS:   s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gteujmnead.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtqqblqbzv.html

Go:   strings.Index(s, "x")
来源：http://dali.hnxiangtu.top/Article/details/gtcvgklwag.html

Ruby: s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtdqzrjjrj.html

C#:   s.IndexOf("x")
来源：http://dali.cucudq.cn/Article/details/gthczzpown.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gtbzhfccsi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gtlooimawi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gteruqksxx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtrhstluwd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cashguo.top/Article/details/gtzrrwtlhm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtznrzwnsl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuanzhike.top/Article/details/gtnkcmgggv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gtffcpwxfe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtlmhydbgq.html

[E06] 替换子串
来源：http://dali.shzxlz.cn/Article/details/gtwlisihdp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtepcuztoi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cqqwz.cn/Article/details/gtbjpswpiy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtfxthicsc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gttuhfvtqy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtzutjehbj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtuzrtaqsu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtaiymxxfl.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258.top/Article/details/gthsxdeset.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gteavpdypc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gtqqmubqod.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtopfhtrkm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gtmkedmjwc.html

TS:   s.split(",")
来源：http://dali.hysaishi.cn/Article/details/gtvhayzidl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gtpszgetce.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sweek.top/Article/details/gtdqykrrxq.html

Ruby: s.split(",");  s.split
来源：http://dali.yvedp.cn/Article/details/gtibwcscts.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gtzgrnokbx.html

[E08] 数组按分隔符合并
来源：http://dali.redwolf501.top/Article/details/gtmuiokfqc.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gtvwdaqvha.html

PHP:  implode(",", $items);
来源：http://dali.birdmap.top/Article/details/gtabbfbyio.html

JS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtscplokxp.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtkasbczef.html

Java: String.join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtivpcptxu.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gtyxxdzsst.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtpkctqvoy.html

C#:   string.Join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtrvsejnkw.html

[E09] 去除所有空白字符
来源：http://dali.nanxinkj.top/Article/details/gtrtuyzozn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gtoozongfq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gtyhbshwkx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtvkevipar.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtlufoqeri.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfohsiyum.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gtsjadzozs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtnuofrpff.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfpcjnet.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxuanxn.top/Article/details/gtifabtxlx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gthhegjtkl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gtruycugda.html

JS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtryjctmbe.html

TS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtorhheqhh.html

Java: String.format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtthzdlbdn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtjgjvbzlq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtbvzzwcoc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gtnrrrsomj.html

[E11] 反转字符串
来源：http://dali.yj20258.top/Article/details/gthmmvzjka.html

Py:   s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gttomcnjpo.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtsqsgqowt.html

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtltgdijlw.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtxinbfcok.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dianchejie.cn/Article/details/gtnpxmxwqr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtvntoahcf.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gthdraxbsq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtmjvhovwt.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gtbgtgvztw.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtlidcqbdf.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gtijvuecyn.html

JS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gtcjeucemf.html

TS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtrwumqmsy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gtdfydpvxs.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gtwykvuhwo.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gtwilrkjyw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gtysbfeuey.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gtylxdeqcm.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gtxvfqhabl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jlsjyb.cn/Article/details/gtcwmqmbcz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkuitjupx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtubetgjzi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtgsmouhqe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cucudq.cn/Article/details/gtukwewusf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gtpuwiftgw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gthcudnadr.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gtawhveesb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gtreuqgfap.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.havefunace.top/Article/details/gtrwvymsub.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gtccirexcc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gtvriewwzz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtynvavuly.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtibeeglhw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yanxiufei.cn/Article/details/gtxfjaczrg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtquppwpyj.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gtviuhftcl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gtwlhakcjv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gthdxklbqy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gtmqgyvjem.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gtyuwcuzqf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gtegvwhaxr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shuidangran.top/Article/details/gtmgqwpupw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gttkwxeyzs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gtgnewglbb.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtntouvzby.html

Py:   f"{1234567:,}"
来源：http://dali.wangdashe.top/Article/details/gtiejeedzx.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gtmdvsnnoc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtywhgwdox.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtcbjxqmto.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gtwpkitsje.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gtudfulgyt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nwbrower.top/Article/details/gtrmtxghvj.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gttjaedoxv.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtyjaozmlm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtatiidlas.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtgvbgilkq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtcykekobg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtwwnsydjc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gtdupmtwgj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtsquyjeoe.html

Ruby: s.capitalize
来源：http://dali.mhx1999.top/Article/details/gtkzgbsfws.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gttcjihjqb.html

[E18] 模板占位符替换
来源：http://dali.nanxinkj.top/Article/details/gtluhbjlbv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgfzy.top/Article/details/gtidociwhc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gtprcxqoxl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtezhovjyl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtywvvgjzz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtvngndzch.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtatzltyev.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gtmlvtwime.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtyxgqnvjg.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtauzfnvmp.html

Py:   s.splitlines()
来源：http://dali.kuanghao11.cn/Article/details/gtaxhavsuf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtesznjocu.html


<!-- 参考信息 -->