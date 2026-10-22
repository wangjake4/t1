代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gt2hmmvxzqk.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gt2dyjhmcso.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gt2ecdmrdjm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gt2kyyjtith.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cheryme.top/Article/details/gt2rritbvdg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gt2vlpephnh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gt2elzztdhw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gt2bpkluyib.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhoulong.xyz/Article/details/gt2gruswmhk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gt2mkcanbud.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gt2enwzrutw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gt2yezeomff.html

[D11] 反转数组
来源：http://dali.shuidangran.top/Article/details/gt2otqkfzci.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gt2adkbtrkx.html

PHP:  array_reverse($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2wodsrkdh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbwbwfsc.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gt2mmiuxckd.html

Java: Collections.reverse(list);
来源：http://dali.316326.xyz/Article/details/gt2qouuzjgl.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gt2goppzeqz.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfgwplop.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gt2qhquzphg.html

[D12] 查找元素下标
来源：http://dali.aibaodan.cn/Article/details/gt2zfglemib.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fljtnots.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gt2anpdeqwn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2vjikeskx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvmoetxj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gt2qitagqim.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2emlnaqch.html

Ruby: arr.index(x)
来源：http://dali.redwolf501.top/Article/details/gt2zaawidyf.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gt2xmdorcim.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqizqagw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.c1oappe.top/Article/details/gt2hwkesnwu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2eqdszmmg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gt2pujephvi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gt2qlzsgrrk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2rsoyytqu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258888.top/Article/details/gt2vzqozlbj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yongpay.top/Article/details/gt2dehpfdtl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pycfn.com/Article/details/gt2xrooqkla.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvneajsi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2crzvumrh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2klwlqtfo.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2taqrkzts.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gt2lsdtvdfl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.smart0.xyz/Article/details/gt2qzpaejed.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gt2jpuhmgid.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjsmauig.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2wwrcqjum.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2jibskboz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gt2cpkbsqlx.html

PHP:  array_unique($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2pcqprifc.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2puaxubpd.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gt2ododmzun.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gt2gbcjguyd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gt2rxvtjpmu.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gt2ypazavji.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpqlailt.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gt2odwxtzsy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2znilhgny.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gt2enarywwb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2nnxrvnch.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2gdetosrt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sysykeji.top/Article/details/gt2yqrbwhzg.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gt2upewgbfb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gt2davoqtft.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gt2rnskrpxf.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gt2vccfltes.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2kedptbsr.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2xsyzqarj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gt2gwglyyje.html

TS:   Math.max(...arr);
来源：http://dali.snrcjt.cn/Article/details/gt2lewhdump.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gt2yjlnupwr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtibqakl.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gt2scdjvabh.html

C#:   list.Max();  list.Min()
来源：http://dali.iojbl.cn/Article/details/gt2znmltepy.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gt2scrajxmp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gt2odqoqrrp.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gt2aguvcxph.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gt2rmykkfhj.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gt2thpevcgu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gt2zhwfqeim.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gt2rmoduunr.html

Ruby: nested.flatten
来源：http://dali.yuanzhike.top/Article/details/gt2uhaxokax.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2gnezipja.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gt2lgelwbzk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rleyidho.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.svipenyu.cn/Article/details/gt2qrtlqvzx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnqzz.top/Article/details/gt2ziynknqz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gt2ztorfiaw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gogol.net.cn/Article/details/gt2vtvmeefd.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gt2nzqoehfk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.vqdsnc.cn/Article/details/gt2ugexksoh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuanzx.com/Article/details/gt2vzphrkgf.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gt2jvykxden.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2dzhrfygg.html

PHP:  array_count_values($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2oasoopce.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gt2tsvddhgv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gt2kflaocvz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gt2pphskzdz.html

Go:   // 手写 map[T]int
来源：http://dali.xuetiantiany.cn/Article/details/gt2gsdvtgax.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gt2sstdgnoa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ivvv.top/Article/details/gt2qglzaqtz.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gt2kjbraojs.html

Py:   x in arr
来源：http://dali.jinqigufen.top/Article/details/gt2qyccghrd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gt2fxmspbei.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2qvrnngqt.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oavcdnui.html

Java: list.contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2zivbkdxa.html

Go:   slices.Contains(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2kkhtbcud.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gt2dfbofdrr.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2scqunwif.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gt2sfaumekl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gt2gjwjircp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gt2vuzwziws.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2scpilbdv.html

TS:   [...arr];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kowvdpwv.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2ozpqjdvn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gt2pascerbq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gt2eoyigejb.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etqpuowe.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gt2bxitmafj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangdashe.top/Article/details/gt2rxydqzhi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2gikezqfi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubkpwlaj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gt2oyfvhtrl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gt2gwanhuum.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gt2ortmqzqo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gogol.net.cn/Article/details/gt2wmfdjxiw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gt2qnkhghjq.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258.top/Article/details/gt2anbdschj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2etygzcje.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gt2bsypxpdo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guowangkeji.top/Article/details/gt2ndetipyd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnqzz.top/Article/details/gt2yylcgbmn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zdqjudy.top/Article/details/gt2xgqtekfc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxuanxn.top/Article/details/gt2dcpkfsat.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cqqwz.cn/Article/details/gt2dtpwavac.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gt2hxkkklxi.html

[D25] Set 集合去重与交并差
来源：http://dali.tianlin.xyz/Article/details/gt2kqkbpuuv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.svipenyu.cn/Article/details/gt2ycaitoyd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gt2xdaknsuu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gt2vzjaubws.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gt2xpsqpibu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2biwhyicl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gt2oavkgazl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.redwolf501.top/Article/details/gt2yneqcteo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gt2mnamtcnu.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zegehoro.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gt2ukjfhfbw.html

PHP:  implode(", ", $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2plvvlnmj.html

JS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gt2cgkcvuof.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2deyszhqh.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gt2nbmuehui.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gt2pxalfybb.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jwugxwbz.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2zlmcworq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2wgxxnxhf.html

E. 字符串处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ereegfrn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ylupkiqf.html

[E01] 拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2huxgyfgc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnqzz.top/Article/details/gt2aptlhctm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gt2lsodidav.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gt2gyzrkamk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gt2aqshhpec.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj202588.top/Article/details/gt2dflzifal.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atzhkiyt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aizwys.cn/Article/details/gt2dmcxzhhh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2ispuhoul.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2piggftub.html

Py:   "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gt2rvcstwee.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2vfuilxfb.html

JS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2dqhesdkt.html

TS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2emftqnbh.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2uqhuphep.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cdnleiting.top/Article/details/gt2twkkqjxw.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gt2sopbyznb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.0kj1m.cn/Article/details/gt2ebxorzlu.html

[E03] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqvrnrzd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gt2cgfznfkw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjhswuzy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gt2ipfjvjww.html

TS:   s.slice(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pryotvzk.html

Java: s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gt2hqnvlkze.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqczxjth.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srdgueha.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gt2vyykvfkg.html

[E04] 查找子串位置
来源：http://dali.ehwqpu.com/Article/details/gt2hlubjyws.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gt2itwzuflu.html

PHP:  strpos($s, "x");
来源：http://dali.yuxming.cn/Article/details/gt2zudectrg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gt2seynkwai.html

TS:   s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2ijnvneqo.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gt2ssvdmeay.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gt2tnvgxoqh.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2bhlgpnzs.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2jzuhtekx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ydzc1.top/Article/details/gt2nsehhawx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2hclnmejv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guowangkeji.top/Article/details/gt2njqcbgvm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2lyylsfst.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gt2ewrgvktw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2zybjrksy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gt2nqquwxhm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gt2hftdqcrv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2odlottym.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gt2vtcmddzf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gt2rveogxsy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gt2pbbocnod.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjvykxqn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kcjfetuq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2jltljacp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gt2ghymnvnu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2pzgytlck.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2cgzhzhba.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gt2ypcirmge.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuanzx.com/Article/details/gt2tgrumwip.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gt2rgxcyuvq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigufen.top/Article/details/gt2qflqlhpq.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gt2absmzrjt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gt2bshvpcir.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gt2cjfrxxoe.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gt2lqlvqwhr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gt2rpzozgub.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gt2ifjomxzw.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ystqpdgp.html

PHP:  implode(",", $items);
来源：http://dali.mhx1999.top/Article/details/gt2rxwksrwm.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gt2dqiudmql.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjjqeabi.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gt2bcbfxbfp.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gt2aaomotdm.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gt2qzxgawqg.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gt2rayshpcf.html

[E09] 去除所有空白字符
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2unpctqdz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcytsnuc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xziqi.cn/Article/details/gt2tfujtrvj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gt2hlgwlqrw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2pivuoers.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gt2mevdrmxy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gt2mkbuwwyq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gt2ztefuijy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gt2egbfeszs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gt2axaiegjh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cashguo.top/Article/details/gt2pzavwlcj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gt2jibxipnv.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2xazscwar.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gt2yhnoxoji.html

Java: String.format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ikkyxhyr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjnwwwmc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2ximcmvpd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.iojbl.cn/Article/details/gt2ykttlzyi.html

[E11] 反转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2rfftzhjy.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjxzkyha.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2ihjacqed.html

JS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2ztmedfdd.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2gyiuzibu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxfjeuvp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsfmzjga.html

Ruby: s.reverse
来源：http://dali.tanke756.top/Article/details/gt2cvgupvok.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gt2kyaaitaa.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gt2kkckadxj.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gt2qjzxzelo.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gt2ckyfousd.html

JS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gt2dhpnygap.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gt2mzdghucc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.redwolf501.top/Article/details/gt2svjcrdsp.html

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gt2whzeomto.html

Ruby: s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2cvwrlbet.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cashguo.top/Article/details/gt2dkiogxmm.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gt2fervxyvx.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gt2wunvohqp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gt2umcobcxy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gt2bhvosbhf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2xkjpqhiw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2prvebnki.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2figitolc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2somspbhg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2fgnoycnc.html

[E14] URL 编码与 Base64
来源：http://dali.chenlongwang.top/Article/details/gt2ldednxhl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jyoumei.cn/Article/details/gt2zouhydzg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezeduksm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenzaomai.com/Article/details/gt2kjfripqz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gt2lybrnczg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsxbooru.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gt2alxyavol.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gt2gbggcyaj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gt2qavquqql.html

[E15] HTML 转义 / 反转义
来源：http://dali.vqdsnc.cn/Article/details/gt2ymscdxem.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gt2oeqfbzta.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenlongwang.top/Article/details/gt2szjvbbkm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gt2tdyfvloe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gt2ceiigagd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.smart0.xyz/Article/details/gt2fvbkzshv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqvrlrrm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gt2simsazec.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2ayutnscx.html

[E16] 数字千分位
来源：http://dali.jyoumei.cn/Article/details/gt2ukeyyzyi.html

Py:   f"{1234567:,}"
来源：http://dali.sysykeji.top/Article/details/gt2rkorwwqu.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gt2qddkhaqo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2cppknjhi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gt2vwnrcrmi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gt2pfjbnvmg.html


<!-- 参考信息 -->