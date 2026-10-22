代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtqboibdxj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdaedybxe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guowangkeji.top/Article/details/gtwdyxtvgj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gtxxylekqi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtvjhoyytk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gttevfcpzl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtspgbpkyp.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtobbdltuv.html

Py:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtavigajwj.html

PHP:  count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnjkaxcr.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtlehqqlka.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtgpcoidyl.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gtqkcqwljq.html

Go:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcabinii.html

Ruby: arr.length; arr.size
来源：http://dali.hammf.cn/Article/details/gtbdwpqpru.html

C#:   list.Count;
来源：http://dali.daxiang520.top/Article/details/gtufkuhadu.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gtriferbbv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gtxswfkgqf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nwbrower.top/Article/details/gttbtygacv.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbbqsmsw.html

TS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtiktrmpid.html

Java: list.subList(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtbitxhlws.html

Go:   arr[1:4]
来源：http://dali.cucudq.cn/Article/details/gtyprspvtn.html

Ruby: arr[1, 3]
来源：http://dali.wangdashe.top/Article/details/gtbztpedhd.html

C#:   list.GetRange(1, 3);
来源：http://dali.zycfv.cn/Article/details/gtjsmcvjck.html

[D08] 合并两个数组
来源：http://dali.sufxvd.cn/Article/details/gtlubklwol.html

Py:   a + b;  a.extend(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtnyylyzmh.html

PHP:  array_merge($a, $b);
来源：http://dali.guowangkeji.top/Article/details/gtavxrvffd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gtkozcgqyu.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gtjhgggkrl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zdqjudy.top/Article/details/gtkdroznxt.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gtbowdclos.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhoulong.xyz/Article/details/gtbibpyeyi.html

C#:   a.Concat(b).ToList()
来源：http://dali.cucudq.cn/Article/details/gtehndnofa.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gtxibsvayo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtdivfqqdm.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtryekpbqw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhengqikj.top/Article/details/gtvtjhycry.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gtpzuaidcq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pengpengdd.cyou/Article/details/gtvkgwgnlt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtzkwavnds.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtvscqjvon.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gtpdvtilsz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gtxdyyfrkx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gaohongyu789.top/Article/details/gtnhxdonle.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtvnsmmtsk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtnbnwdyjb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtrprlvwxr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.birdmap.top/Article/details/gtmbocimon.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gtazsukwcv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.feifeiyinyue.top/Article/details/gtmpmcxrav.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigfzy.top/Article/details/gtvtodbuwg.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gtcwfceebm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gtepvfwarq.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gtehqnqdis.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gtsdpspkjs.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gtgmyylojm.html

Java: Collections.reverse(list);
来源：http://dali.yvedp.cn/Article/details/gtgurkcggw.html

Go:   slices.Reverse(arr)
来源：http://dali.birdmap.top/Article/details/gtbvgouvgn.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gthtyuhbys.html

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gtjebdgjvx.html

[D12] 查找元素下标
来源：http://dali.feifeiyinyue.top/Article/details/gtxoqvprrm.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gtwapxidjp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yvedp.cn/Article/details/gtboimupet.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtwlvrrwmj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gtgswxsqao.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gtdhoiafky.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtnqgslzgn.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gtwqgrvvfw.html

C#:   list.IndexOf(x);
来源：http://dali.daria6918.cn/Article/details/gtoqreeqde.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gtkfbutibk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gaohongyu789.top/Article/details/gttajimmtq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gtufcymfbj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtgvmmnfei.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtatngshyc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgfzy.top/Article/details/gtbergufpg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gtrqvfqjse.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ydzc1.top/Article/details/gtpkqftqvn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtcjygavwc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhongyouzk.top/Article/details/gtecqnzwhn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtywhglikn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gtaohgliec.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtlnxfdsht.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gtgulcbhnt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtfabzsgns.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtvidhubze.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gtlzpaclrw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtoehhuycu.html

[D15] 去重
来源：http://dali.hnxiangtu.top/Article/details/gtenbzhxbq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gtetltbygq.html

PHP:  array_unique($arr);
来源：http://dali.svipenyu.cn/Article/details/gtphkdwjnl.html

JS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtsorxpngb.html

TS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gttlimajza.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gtvjynbpyq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gtmyxeojah.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gtzkpvlrly.html

C#:   list.Distinct().ToList()
来源：http://dali.wangdashe.top/Article/details/gtahsianvv.html

[D16] 求和与平均值
来源：http://dali.ydzc1.top/Article/details/gtphbtvdvg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtuohynlrx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtapzvktxw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtagxbgrwj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gttiovbtqb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gtilcuwlpm.html

Go:   // 手写循环累加
来源：http://dali.hywenlv.cn/Article/details/gtcftrhwek.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gtkluziasq.html

C#:   list.Sum();  list.Average()
来源：http://dali.gaohongyu789.top/Article/details/gtmnrowvtm.html

[D17] 最大值与最小值
来源：http://dali.redwolf501.top/Article/details/gtnlvqfxhe.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gthmoqtbau.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gturfdpwns.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gthlfehtvq.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtmrupdczn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yanxiufei.cn/Article/details/gtfdpkwybw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtlgozwtpe.html

Ruby: arr.max;  arr.min
来源：http://dali.aibaodan.cn/Article/details/gtecxxzzdo.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumddrwct.html

[D18] 扁平化嵌套数组
来源：http://dali.dashuyun.cn/Article/details/gtmgqpiwtm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gtmfzhmqqr.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gtzvttoivq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gtcgcnhrjv.html

TS:   nested.flat();
来源：http://dali.tanke756.top/Article/details/gtmtjznzco.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gtobobwcov.html

Go:   // 手写双层循环
来源：http://dali.hfpthk.cn/Article/details/gtshzzcrou.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahxvxhid.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fengsongda.top/Article/details/gtlozjpdab.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gtwxmftlvk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gtptvjygjy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gtlucrmeff.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gtbaxxokcx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gtixchexmk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhongyouzk.top/Article/details/gtymsbkpzi.html

Go:   // 手写 map[string][]T
来源：http://dali.xuetiantiany.cn/Article/details/gtrxcahflo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.redwolf501.top/Article/details/gtqemnvypj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gtvaysinsd.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gtoqbgetkt.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtwajvvduo.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtzclqlyay.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtpjzacret.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtxcnsxjqp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gtsqlvtpgp.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gtvevojsct.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gtkijqndvc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gtvxjuncmr.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaopvnsye.html

Py:   x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkcssjxg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gtxrtprgup.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtiuvwqklj.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtwtbauezu.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtvnrsgqim.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtsiooiyzf.html

Ruby: arr.include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtcaqujpln.html

C#:   list.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtmukyzozm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gttoxyjqti.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuovlvpkb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gtzkbsvhua.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuxming.cn/Article/details/gtapummivb.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtuwtjmhew.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gtokiakxib.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gthbdovnpl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gtdcrlewtt.html

C#:   new List<int>(list);
来源：http://dali.c1oappe.top/Article/details/gtabydchyx.html

[D23] reduce 累积计算
来源：http://dali.hongshengwenyu.top/Article/details/gttqdevtar.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gtwikquvyf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.mhx1999.top/Article/details/gtzgrjfgpt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtnlnwrnmz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtewcmlhpi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gtwmiuqxod.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gtndvkfhzz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gtiskbutlb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gtclxigdqe.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gtcyxeukku.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhixingplan.top/Article/details/gtydiecouf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gttfxxuevv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvboktbxf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtpjltfmfx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gtiugutefy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gtrmcyzqhj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hysaishi.cn/Article/details/gtkecyimnn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hywenlv.cn/Article/details/gtqyeatjpt.html

[D25] Set 集合去重与交并差
来源：http://dali.sufxvd.cn/Article/details/gtcirfasly.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gtazmhtpxh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gttklgtgow.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtewizfcic.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtbggmibta.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guannengcc.top/Article/details/gtvqljwhkx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hywenlv.cn/Article/details/gtyecodsqs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gtvkachzco.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gthrzdfttu.html

[D26] 数组转字符串
来源：http://dali.yongpay.top/Article/details/gtifdwjnqu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtbbmrjccl.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtqzdapdgy.html

JS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlezagiho.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtiezdphhg.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtunzkzufg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258888.top/Article/details/gtbvdfbfym.html

Ruby: arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gthnxhovgw.html

C#:   string.Join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvhgnmlf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwnyoilch.html

E. 字符串处理
来源：http://dali.hywenlv.cn/Article/details/gtlficsihm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmizltrss.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbicxmgj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtoajdoqca.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yangfankeji.com/Article/details/gtdlvoblzb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtqqcxhilz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtjaqejmom.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yvedp.cn/Article/details/gtfaqbdoky.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtdrhwofff.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gtlrazfcyd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozezudow.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtiznxdrdk.html

Py:   "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtovdwopiw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zdqjudy.top/Article/details/gtynqluzuu.html

JS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtkrhneasr.html

TS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvabmjgrv.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gthfbnbleh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258.top/Article/details/gtwglslydb.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtbirmiagf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtmnyjupxg.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtufekzjdf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gtbjzokxvq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtjvvtnefh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtlhtesjct.html

TS:   s.slice(1, 4)
来源：http://dali.yonumen.top/Article/details/gtmjjfrkbt.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtlybsbggn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.iojbl.cn/Article/details/gtaqtcozeq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cdnleiting.top/Article/details/gtieblrpdd.html

C#:   s.Substring(1, 3)
来源：http://dali.cdnleiting.top/Article/details/gtsofxhkfm.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gtqmgmlzng.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtxkkyittd.html

PHP:  strpos($s, "x");
来源：http://dali.dashuyun.cn/Article/details/gtzdiwzkmw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gtwfroxzpt.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtemxfudzb.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtggwmsabz.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gtqiuclktz.html

Ruby: s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtnqizcjbr.html

C#:   s.IndexOf("x")
来源：http://dali.nwbrower.top/Article/details/gthryradol.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yangfankeji.com/Article/details/gtgckfnyan.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhghbnyg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guowangkeji.top/Article/details/gtnimtuelp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtpjqhoeyt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gtlqijyzgx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtpchatika.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigfzy.top/Article/details/gtjdwjqany.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gtbtejzvil.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqlexolc.html

[E06] 替换子串
来源：http://dali.hysaishi.cn/Article/details/gtfwftmaov.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gtjqzylnqx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gtlpitdevs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtaogluoji.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtlwkfjelt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtgkrraosh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtaozhfnte.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtdqtwjuxg.html

C#:   s.Replace("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtnucdesez.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gtchtqvhbz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gtlaidwquz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hammf.cn/Article/details/gtalccbnfs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhoulong.xyz/Article/details/gturtuwedq.html

TS:   s.split(",")
来源：http://dali.yongpay.top/Article/details/gtnlzjsywu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhixingplan.top/Article/details/gtauwvmdwz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gtqwldussd.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gtllnsdxcp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tian-w.cn/Article/details/gtrwjvknyp.html

[E08] 数组按分隔符合并
来源：http://dali.zhoulong.xyz/Article/details/gtjdpqbcnj.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gtarlqnvmf.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gtvyremlzo.html

JS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gthqqcbgmn.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gtohaanoyr.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtggtpanme.html

Go:   strings.Join(items, ",")
来源：http://dali.yuxming.cn/Article/details/gtaxgjjwce.html

Ruby: items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtcjxgkyik.html

C#:   string.Join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtyyextkla.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gtsfwbktji.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gtksuwoohm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtdasszvhx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtlvhjiesf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtaznxyvau.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtmrbenmfn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gtlhxosfuk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gtehfczgru.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gtcbmluvan.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gtrydahkvj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtpafdxrmv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aibaodan.cn/Article/details/gtgydssjob.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtfrnheiul.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtlbvzfulz.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtuuzwokgz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtebhfkhzj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtydukzzlg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gtmvnsaoqk.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlylyezyu.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtymxmvpdd.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvynmthew.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtgcauxjrv.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtqhigftee.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gtucyukhce.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gtisebnfkc.html

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gtokrcydhz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtwbiyosox.html

[E12] 统计某字符出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtyckdigcp.html

Py:   s.count("a")
来源：http://dali.ivvv.top/Article/details/gtmhttkvqv.html


<!-- 参考信息 -->