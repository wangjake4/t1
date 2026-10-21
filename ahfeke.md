代发 wailian999

PHP:  sort($arr);
来源：http://dali.yj20258888.top/Article/details/gtslpahvtn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gthfszscsg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gtpxtdyilo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pycfn.com/Article/details/gtvkbxfott.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvznwcvg.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzibkdrjr.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gtfupnfqax.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gogol.net.cn/Article/details/gtblzqvyyo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gtutraldrn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gtnxzurlgn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtiurxzwdq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtuzjtfwfy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yanxiufei.cn/Article/details/gtbzsdaacd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gotoacloud.top/Article/details/gtvpwimaix.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tianlin.xyz/Article/details/gtscmohcjk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gtwmyesqfe.html

[D11] 反转数组
来源：http://dali.jiagoushi.top/Article/details/gtfqidsxro.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gtuhhzdfph.html

PHP:  array_reverse($arr);
来源：http://dali.zhengqikj.top/Article/details/gtnwvujgnx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqdrvfhu.html

TS:   [...arr].reverse();
来源：http://dali.hammf.cn/Article/details/gtjsjtxblq.html

Java: Collections.reverse(list);
来源：http://dali.nanxinkj.top/Article/details/gtvosryupi.html

Go:   slices.Reverse(arr)
来源：http://dali.xuanzx.com/Article/details/gttyyyvhaq.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gttuwowmmq.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gtmjokigyq.html

[D12] 查找元素下标
来源：http://dali.c1oappe.top/Article/details/gtuovaildh.html

Py:   arr.index(x);  x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtxdmbxhut.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jianghu66.top/Article/details/gtipmfbsku.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtxwsijcul.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtyrvzhjwo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gttgfkurup.html

Go:   slices.Index(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrfnopcu.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gtmxuurlng.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gtlwvecedh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcrbrbzh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gtxdywozzf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtzpaljjks.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtaxemfzuf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtkvutonnq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gzhubu.top/Article/details/gtpbljhgrm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.smart0.xyz/Article/details/gtilwmilox.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenjidiqi.icu/Article/details/gtepgbjbet.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtetfoynry.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gtnxlqzmpd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daxiang520.top/Article/details/gttzydaxub.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtdxfopcrg.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtqqqmtcez.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfoidodzx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tianlin.xyz/Article/details/gtsrqwqkhg.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtkpwafpln.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgxzgpom.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtbpdyuepg.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gtzxqwppwk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtwndvvgej.html

PHP:  array_unique($arr);
来源：http://dali.meibo888.top/Article/details/gtpkmlqzfu.html

JS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtdnwhlawh.html

TS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtmdahurks.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gtxronjmlg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daxiang520.top/Article/details/gtznzsmnnd.html

Ruby: arr.uniq
来源：http://dali.haohaochexian.top/Article/details/gtoxsdeaqq.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gtnjoochfz.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gtavroyggj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtksejbyxp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtnztkmbnh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtzsvqsbwo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtzuurgtkr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gtrabsbosz.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gtainxazpj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258.top/Article/details/gtaitozgft.html

C#:   list.Sum();  list.Average()
来源：http://dali.vqdsnc.cn/Article/details/gtdokbzjnb.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gtoxbvwtna.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtaguufopt.html

PHP:  max($arr);  min($arr);
来源：http://dali.haohaochexian.top/Article/details/gtugaicosw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daria6918.cn/Article/details/gtczevhmwk.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gtdvrkfgtf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.bjfxy.top/Article/details/gtrzaqhsue.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gtnhgytgjs.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gtoeopmyqa.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gtrqcoflot.html

[D18] 扁平化嵌套数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbmwcrha.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gtebybjkiu.html

PHP:  array_merge(...$nested);
来源：http://dali.zhixingplan.top/Article/details/gteiqcpowp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigufen.top/Article/details/gtfptzoshx.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedxmsecz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtgaujod.html

Go:   // 手写双层循环
来源：http://dali.bjfxy.top/Article/details/gtqsdqboqe.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsipnhlij.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gtgscvmzoh.html

[D19] 按字段分组
来源：http://dali.cqqwz.cn/Article/details/gtsfinfjus.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gtydxcmtda.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gtaxdnmqsg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cheryme.top/Article/details/gthlhsrepo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtyageeyjg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuanzhike.top/Article/details/gtzbzweiks.html

Go:   // 手写 map[string][]T
来源：http://dali.redwolf501.top/Article/details/gthapgmpwj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aizwys.cn/Article/details/gtueforjuq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenlongwang.top/Article/details/gtdoicvypr.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gtpicqjcpc.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtkgvqxemr.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gtpzlkqwfb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtqfafxwui.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gttqevlnjt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.andypj.xyz/Article/details/gtcbmifzvp.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gtymwuutxa.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gtthsamldi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gtsjxasdzf.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtglasdjwm.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gtuxgkeobb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cheryme.top/Article/details/gthpihaeiq.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtsincahnp.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtygwugulq.html

Java: list.contains(x)
来源：http://dali.ydzc1.top/Article/details/gtkbgtmbsf.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtetqgacrr.html

Ruby: arr.include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtbkvnrram.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtpbphclow.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ehwqpu.com/Article/details/gtpxulpkwg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dashuyun.cn/Article/details/gttiqaqqzy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuuboatt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ybcxt.top/Article/details/gtuhcdmcgw.html

TS:   [...arr];
来源：http://dali.jinqigfzy.top/Article/details/gtacagjhmu.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtirzxytdz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sweek.top/Article/details/gtibctebms.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gtnwyomytj.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gtvneggvcq.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gttqniluot.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenlongwang.top/Article/details/gtuywttcss.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtngnhkuez.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gtnrdseztv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtcooccghy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gtcgvhtlzc.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtnbsyltek.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gtqjqjempo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuanzhike.top/Article/details/gtmqcztkpl.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gtfqceuikv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gtaolenyio.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gtaybhcbzr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258888.top/Article/details/gtbfpmigir.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtsrxybggk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.0kj1m.cn/Article/details/gtxvllkjag.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuxming.cn/Article/details/gtvxhhmkuw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gtabkrhoiu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gtxoeeuhsk.html

[D25] Set 集合去重与交并差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrtzhwra.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtwnowatbo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtdhaokwjx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gtmwuvbexb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdplmsyak.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gteuguygqv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hfpthk.cn/Article/details/gtymcelmto.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gtnddfmzqw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtuuagssps.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gtkereagvy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.meibo888.top/Article/details/gtsnjodnyf.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpdpxnxp.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtrzltxpli.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtlrzesyio.html

Java: String.join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtlncoucfw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gtgiiljfnw.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtgpfnorgy.html

C#:   string.Join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtcdewxmwy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gttilpgqkk.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gtzhcuzzse.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqezauzie.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdhneafk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.bjfxy.top/Article/details/gtljfcdwqe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gtyzdmioac.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gtlixsqmsf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtchyldukm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhengqikj.top/Article/details/gtmuvorbxi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gtikbdmvzj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gttglzvrja.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtstpopnpz.html

[E02] 重复字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtirfcphpw.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtlppmpfza.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gtbbhqhefu.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtepvzsurl.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtvkiykgcn.html

Java: "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtaagppdse.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgygxhcai.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtshokphpo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.redwolf501.top/Article/details/gtogprjpwq.html

[E03] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtkmoyxndo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gtdczrkodp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtbcsprwew.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gthlzpzjpb.html

TS:   s.slice(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtzxstuppu.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtnhgrkyfc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibzzqkpj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangdashe.top/Article/details/gtuqreguue.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gttskwigda.html

[E04] 查找子串位置
来源：http://dali.jqgufenzy.top/Article/details/gtiruvefdu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gtzykubryl.html

PHP:  strpos($s, "x");
来源：http://dali.yueranfly.top/Article/details/gtfkapfhdx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aizwys.cn/Article/details/gtvcsaqsrq.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gthbhtvpgj.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtxmildngp.html

Go:   strings.Index(s, "x")
来源：http://dali.smart0.xyz/Article/details/gtcyopbgit.html

Ruby: s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtklcgzkqu.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlxhuzvo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xinyue.icu/Article/details/gtlayqenxy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gtiwspqpqk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gtbgxyasqy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtubftrfio.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gtmkqcfetg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiuacxdcb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhongyouzk.top/Article/details/gtyswfvcde.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtmxriqgnu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.havefunace.top/Article/details/gtbvtwsaeo.html

[E06] 替换子串
来源：http://dali.gotoacloud.top/Article/details/gtgzebskmr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtlnkdocrv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhongyouzk.top/Article/details/gtpbhjszae.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtoxzoywws.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtnoadrxkj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtszjhmgvy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtbpcuxvmz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtnculrwmo.html

C#:   s.Replace("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtpikniqev.html

[E07] 按分隔符拆分
来源：http://dali.nwbrower.top/Article/details/gtvwcvftlq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrkgylnz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtijuhucio.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xinyue.icu/Article/details/gtcfeomvld.html

TS:   s.split(",")
来源：http://dali.yonumen.top/Article/details/gtmijvwnri.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hammf.cn/Article/details/gtuijciyvq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhkwnmkw.html

Ruby: s.split(",");  s.split
来源：http://dali.gogol.net.cn/Article/details/gthlloaolb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ehwqpu.com/Article/details/gtbgkhrauf.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gtxdsdmfnv.html

Py:   ",".join(items)
来源：http://dali.jiagoushi.top/Article/details/gtorjzxxst.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyolndso.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtyuhcofyx.html

TS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtexsinhjd.html

Java: String.join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gtlljbojbw.html

Go:   strings.Join(items, ",")
来源：http://dali.yongpay.top/Article/details/gtswfgrtio.html

Ruby: items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtclhebbmv.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivuglxau.html

[E09] 去除所有空白字符
来源：http://dali.hywenlv.cn/Article/details/gtssusygtp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtzckfnfle.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gtgibpyhra.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtkdswruax.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtqtesovpe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtzxqyajdb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gtlmasmimx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gthnntzods.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gttmssunro.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gtwesuzbuz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258.top/Article/details/gtaxgmreyq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gtqhwczksu.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinwobjea.html

TS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtqfiwxcnu.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtuakslght.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtrqjfylhm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtmignajhq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gtdvplqdyl.html

[E11] 反转字符串
来源：http://dali.guannengcc.top/Article/details/gtlhdtoslu.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtgeyswewi.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtqyqxfwhx.html

JS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtobnxgbhw.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtdxxyaguo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hammf.cn/Article/details/gtgywkpqhe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gtadcphxgr.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtdbzwswvf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtmnufqxta.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gthckfhvuw.html

Py:   s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtjigulejq.html

PHP:  substr_count($s, "a");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxurzlxw.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtxjsacvoa.html

TS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtklvmbwdx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gtcsznnxmk.html

Go:   strings.Count(s, "a")
来源：http://dali.sweek.top/Article/details/gtpklfkibw.html

Ruby: s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtwuqqviys.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gttmactrel.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gtzidbyase.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtfuhgwggi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gtodbdncwp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtonvbogee.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtrythasrr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtzvnsmqjg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gtkljzrdjm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cashguo.top/Article/details/gtxzxvhgay.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtqwibwvye.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gtehjewelj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxinkj.top/Article/details/gtmtxcxqkn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlefizrln.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuanzhike.top/Article/details/gttlthrzrh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gtxasmmdlb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gthdnjzdgz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gtopsnkhvq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hongshengwenyu.top/Article/details/gtymopjoff.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.smart0.xyz/Article/details/gttbfwpzwh.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gtolxnrpcv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtkdhmwlao.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gteijkphac.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gtttfdayhj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gtfpawoldp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gtnktrjeik.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cdnleiting.top/Article/details/gtcorfksxn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gtwyewcunk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuaanqgqb.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gtopfvjlir.html

Py:   f"{1234567:,}"
来源：http://dali.shzxlz.cn/Article/details/gtvfvebdau.html


<!-- 参考信息 -->