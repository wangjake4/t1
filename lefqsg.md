代发 wailian999

[D11] 反转数组
来源：http://dali.havefunace.top/Article/details/gt2ammdmyxs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gt2entrccix.html

PHP:  array_reverse($arr);
来源：http://dali.ybcxt.top/Article/details/gt2syaaxrbe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gt2jjydnlsq.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gt2kcqxepmu.html

Java: Collections.reverse(list);
来源：http://dali.aizwys.cn/Article/details/gt2sgnfsoph.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2iwabppkp.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gt2slnnwxmi.html

C#:   list.Reverse();
来源：http://dali.jqgufenzy.top/Article/details/gt2cboudnhc.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gt2whbrkbhd.html

Py:   arr.index(x);  x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvflmlca.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gt2jycbpcne.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2vqrhlnpc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gt2oymyrmbv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xylfe.cn/Article/details/gt2ccrcbvzg.html

Go:   slices.Index(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2msydipdt.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gt2rdwfvsgc.html

C#:   list.IndexOf(x);
来源：http://dali.wangdashe.top/Article/details/gt2hbulkris.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bowokdhb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2zcdkbukn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2tixfewdx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggaqfule.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hqvpousf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2hmllnwgj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tanke756.top/Article/details/gt2lpvocxgx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xinyue.icu/Article/details/gt2byivkwxd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2ijjsffia.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ampwcvkg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gt2bhzcfmlg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2xtrsbask.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gt2soqmcnau.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gt2fzjhoflf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2nnfkhsmf.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gt2cfkyqmgv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gt2sjyrtzol.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2myuezmrj.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gt2blcnhmzb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gt2lmkpjvyn.html

PHP:  array_unique($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2guvexlbb.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2jyuppfpn.html

TS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2lkgbuyrw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hysaishi.cn/Article/details/gt2meekllwn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjqugjit.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gt2vxzozxfl.html

C#:   list.Distinct().ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2enwvjfzc.html

[D16] 求和与平均值
来源：http://dali.xziqi.cn/Article/details/gt2pzxiemxs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2hirrmpxd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gt2ssrwakgt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2eboxzxic.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gt2kapffmgi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgfzy.top/Article/details/gt2jzdnktaf.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gt2arujelqp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nwbrower.top/Article/details/gt2tqbiapcp.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gt2cdkrnaao.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gt2lsgeqecz.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2zbqgjkne.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gt2hlmzwutc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gt2zftcpmzb.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gt2zicblcbp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gt2nspikgab.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gt2nabeivns.html

Ruby: arr.max;  arr.min
来源：http://dali.andypj.xyz/Article/details/gt2nbyjdatg.html

C#:   list.Max();  list.Min()
来源：http://dali.daxiang520.top/Article/details/gt2zalghqom.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gt2tkuszare.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yangfankeji.com/Article/details/gt2cofevcfj.html

PHP:  array_merge(...$nested);
来源：http://dali.bjfxy.top/Article/details/gt2dntdslnw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gt2zxvmavyx.html

TS:   nested.flat();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ayynunnz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2ituxonuc.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gt2muoipjwx.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gt2dpfinxgw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2fbspkpbe.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gt2eawhglkw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gt2iuanmlov.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gaohongyu789.top/Article/details/gt2ahamxpqa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sysykeji.top/Article/details/gt2nulamzub.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gt2qivnreag.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gt2njlyyhby.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urwqkaed.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gt2labldmak.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gt2idyxcgtv.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gt2oyruiovt.html

Py:   Counter(arr)
来源：http://dali.ivvv.top/Article/details/gt2tcjwabpw.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gt2bapvnndl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2fapiemfx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gt2jeyibmvk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.mhx1999.top/Article/details/gt2vzxevajl.html

Go:   // 手写 map[T]int
来源：http://dali.tianlin.xyz/Article/details/gt2ewzyfalu.html

Ruby: arr.tally
来源：http://dali.9152youxi.cn/Article/details/gt2qoaznnxi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gt2wmgdymuk.html

[D21] 判断是否包含某元素
来源：http://dali.c1oappe.top/Article/details/gt2vvvjygcv.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gt2ypzgjibk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cheryme.top/Article/details/gt2fsqxxqjw.html

JS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2cihcepxu.html

TS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2fsekfigl.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2rodugfws.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2cygcitus.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gt2mxyzmazw.html

C#:   list.Contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2famobueg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gt2rutfyszt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gt2vhkgxyen.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnxiangtu.top/Article/details/gt2pdzynqwc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gt2lvusfwjk.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gt2hbdqpslo.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gt2sbwbrybp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gt2hxjxatqy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gt2ggxuzcja.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gt2lbolxzym.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gt2yfzwqbte.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258888.top/Article/details/gt2frszajpv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkssyeef.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gt2mppaexno.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2avodgfvz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gt2fchdtdyf.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gt2plnkupyc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbmgvcbd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gt2hwqkfele.html

[D24] 字典 / Map 基本操作
来源：http://dali.zdqjudy.top/Article/details/gt2djsxzqxd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxinkj.top/Article/details/gt2vgflblcl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gt2xlrsgxds.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gzhubu.top/Article/details/gt2vcrbyeki.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2zetznxlm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.birdmap.top/Article/details/gt2hwgczaes.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gt2mcmtgqvc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yvedp.cn/Article/details/gt2vsizmjrc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuxming.cn/Article/details/gt2erumsqsb.html

[D25] Set 集合去重与交并差
来源：http://dali.316326.xyz/Article/details/gt2jupjapgj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gt2gluayqle.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ydzc1.top/Article/details/gt2zsujabln.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zycfv.cn/Article/details/gt2wasvwyju.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ivvv.top/Article/details/gt2rzjewxkr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2migqokvg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sweek.top/Article/details/gt2kkvahnrs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gt2lnmvymnp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gt2buiksayx.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gt2rtlpnogm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2lqgqsdxt.html

PHP:  implode(", ", $arr);
来源：http://dali.c1oappe.top/Article/details/gt2tlphptrs.html

JS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlyyqzse.html

TS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gt2ivvvaseg.html

Java: String.join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aaqdkpsq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2ulolgmef.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2wgmiqijr.html

C#:   string.Join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gt2epkeyiqi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ayjudhrd.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gt2cthtnhok.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2jngkjioj.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2ogpvjajp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.c1oappe.top/Article/details/gt2wauorfph.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gt2hcwtyrgv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gt2yxnpfned.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2qmzindyl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gt2okyncetu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gt2pqnwfmfy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gt2iitgwexv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2eeqgvhur.html

[E02] 重复字符串
来源：http://dali.hnqzz.top/Article/details/gt2idyjsuvw.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2jegyuxxa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cucudq.cn/Article/details/gt2uuuqgdvf.html

JS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2gqvghoap.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jnjfehjt.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2juudctze.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cqqwz.cn/Article/details/gt2cfmmvvby.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gt2mprytvdm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gt2bywpfrxc.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gt2oblmjumw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gt2zimwrxnh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sweek.top/Article/details/gt2sdrqbvly.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2xwscupya.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2zptozhjc.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gt2exlwsfas.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gt2ujqyfblk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gt2gnajocrj.html

C#:   s.Substring(1, 3)
来源：http://dali.zhixingplan.top/Article/details/gt2lbetvgbu.html

[E04] 查找子串位置
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2icweztuz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gt2wwdeiouu.html

PHP:  strpos($s, "x");
来源：http://dali.sysykeji.top/Article/details/gt2rkmfvtwg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gt2cfnxclma.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2axcvrfhp.html

Java: s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2zylgrztx.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gt2ckhjhhtp.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gt2jhecscyh.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2pnisrpav.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gt2cfouazfq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gt2cbbwpven.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj202588.top/Article/details/gt2rgwjtcgw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2itivexyn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gt2lwnorysp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2iuczgvco.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yangfankeji.com/Article/details/gt2omctpkcg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gt2iuzhrpqf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gt2cftrzurf.html

[E06] 替换子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttgvffux.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gt2ecyqeeiw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2wmkesqva.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2lonhlylw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2eraitwmk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2ziopvyzv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gt2mhzzlbys.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2comblbzt.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydiwvuwj.html

[E07] 按分隔符拆分
来源：http://dali.dianchejie.cn/Article/details/gt2namoqpvl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gzhubu.top/Article/details/gt2xaitrfhx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2asssgrbt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtuztuoh.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gt2cubutrpm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yueranfly.top/Article/details/gt2uueueayx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2xjzoceej.html

Ruby: s.split(",");  s.split
来源：http://dali.tanke756.top/Article/details/gt2bcmkbuji.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenlongwang.top/Article/details/gt2abjgayyq.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gt2otcxexwk.html

Py:   ",".join(items)
来源：http://dali.zhixingplan.top/Article/details/gt2xbthtgye.html

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gt2nhzruiup.html

JS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2gdhztpwo.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gt2zzrsyhlw.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofqukfag.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gt2ogerceuf.html

Ruby: items.join(",")
来源：http://dali.zycfv.cn/Article/details/gt2fbecjypu.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gt2dsyknojv.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gt2utobmaws.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vlxqskju.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zycfv.cn/Article/details/gt2whpwdqkg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2dawcmkbx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hozedxzg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gt2lwaerson.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gt2mcdwziny.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yonumen.top/Article/details/gt2kwrlpqmv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2pyqodayh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gt2oerbxyom.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnqqoqms.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gt2qbgofzjv.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2mugreacr.html

TS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pugatkan.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2ntcihrjc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gt2jndhjjug.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfoahjlx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ivvv.top/Article/details/gt2gobiiecv.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2odwmltkr.html

Py:   s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gt2qfuwibrf.html

PHP:  strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gt2bvujzuzo.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2tthttisp.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2rwdjxmth.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2eprethmm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gt2mralpnci.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2gpetueid.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gt2yagllcre.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gt2bkzogzdb.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2srtmpkwl.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2teklrbcy.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2renkqfdw.html

TS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gt2bgdjfsdc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gt2rgyixtbe.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zquijxcq.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2mfruhste.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gt2olehucpw.html

[E13] 逐字符遍历
来源：http://dali.hnqzz.top/Article/details/gt2zfeuxqde.html

Py:   for ch in s: print(ch)
来源：http://dali.zhoulong.xyz/Article/details/gt2itdgpwfr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gt2fruudbai.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2excizqvw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2doenhoeb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2xckefwip.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gt2unfsdltl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhvngnfx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2pmzgqhni.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gt2pxbepkao.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.0kj1m.cn/Article/details/gt2tbuttrfb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aibaodan.cn/Article/details/gt2slcqmuzl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gt2snlmouoj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yangfankeji.com/Article/details/gt2ubpvljmr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gt2haucfmtw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gt2dfvdjewu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gt2dsgxdppo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gt2crahazrt.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gt2vigfyzgh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gt2hvjtxnrs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gt2qjylfppk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuxming.cn/Article/details/gt2jyevados.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2phyxfyjn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ehwqpu.com/Article/details/gt2nhmzojob.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gt2ptypzpvw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sscyvbwd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fengsongda.top/Article/details/gt2nvkucaoo.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gt2tthmoboe.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gt2hjwtmymx.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gt2yojnterb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gt2jsbejsqj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ryvjdwjz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gt2sgmmcubr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gt2lktipgnw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hysaishi.cn/Article/details/gt2odqptzsq.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gt2syzwrprt.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gt2gufkefju.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gt2rznlskaj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdkzihau.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvkzngmu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogwwkdka.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pycfn.com/Article/details/gt2tnollvkq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gt2mfwkottb.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gt2cmntjqkm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gt2tvzlytjg.html


<!-- 参考信息 -->