代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtdkwkczyz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gthjomtjts.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtcefqfibk.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtpcdakkxy.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtwidtemuu.html

PHP:  count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgzaljtm.html

JS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtejnlenlg.html

TS:   arr.length
来源：http://dali.yongpay.top/Article/details/gtzkhkmuid.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gtgxbrldab.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxdxftqu.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gtniruntdf.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gtphlzgrdr.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gthuddoxcc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gtxbgksenq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.c1oappe.top/Article/details/gtyoxafhfw.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtmmhwrien.html

TS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtoterudua.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtphdtpxda.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gtwitzdhzy.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gtfvrgqxak.html

C#:   list.GetRange(1, 3);
来源：http://dali.ivvv.top/Article/details/gtllqopaia.html

[D08] 合并两个数组
来源：http://dali.xuetiantiany.cn/Article/details/gtftqmzgkx.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlccxewd.html

PHP:  array_merge($a, $b);
来源：http://dali.cqqwz.cn/Article/details/gtrajqcbrq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daria6918.cn/Article/details/gtwkncibds.html

TS:   [...a, ...b];
来源：http://dali.jinqigfzy.top/Article/details/gtdbcofjkg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtuknletqe.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gteizbsjeu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jiagoushi.top/Article/details/gtzdtoorpa.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gtbgdirwjy.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gthmjsaxey.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtaspfduio.html

PHP:  sort($arr);
来源：http://dali.cucudq.cn/Article/details/gtpkptodjc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gtmbagiixd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuoafqdbj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dianchejie.cn/Article/details/gtwslazjtr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtgwykbcrr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gthxegqxzy.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gtmllpldmx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwirahha.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gtaidfymal.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtwntfojlz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtqxlyalqu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtbekeqrnk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fzhhl.top/Article/details/gtmwmwlugy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gogol.net.cn/Article/details/gtczfbshou.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenzaomai.com/Article/details/gtmgwavwcd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhengqikj.top/Article/details/gtpobylrpv.html

[D11] 反转数组
来源：http://dali.hysaishi.cn/Article/details/gtqghvpdid.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yonumen.top/Article/details/gtxbbkfnie.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtsczrizxo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ehwqpu.com/Article/details/gtbpnvhlgx.html

TS:   [...arr].reverse();
来源：http://dali.xuanzx.com/Article/details/gtvwisiufl.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtxysabcmq.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gtsjxbppts.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkzingzs.html

C#:   list.Reverse();
来源：http://dali.xuanzx.com/Article/details/gthvftnmjc.html

[D12] 查找元素下标
来源：http://dali.tianlin.xyz/Article/details/gtdyzubaks.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtybmptiix.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gtdegtjcqu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gtkirnlaqf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtnwipepva.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gtictrwjwk.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtmilzndxf.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gtifzqihnu.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gtswwhxgnx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhongyouzk.top/Article/details/gtaqolpozk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtzntxgehn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sysykeji.top/Article/details/gtpdrvbngc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gtzlqcsiiw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtigjzdddv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gtgeapyccu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gtzphadluw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guannengcc.top/Article/details/gtmeuywlrr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzxmrqzt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gtaaxgzhqa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.haohaochexian.top/Article/details/gtdvggvyuo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gturysbgse.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtxpfmlled.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtrmedqdcu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtckipkcli.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtezvnqhig.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrcjtman.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtixhqwvwp.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gtslpiqyeo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gtkvbgosgh.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtemmlhlth.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtpvjdcqqe.html

TS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtozbhhznh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj202588.top/Article/details/gtzdtjyfmr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gtmijwpfkl.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxgfnqme.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gteapaouaq.html

[D16] 求和与平均值
来源：http://dali.ehwqpu.com/Article/details/gtjnjczxpd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gtvebxmqmv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtydgvyzlw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtpezycshz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtfobgvhbf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvwrvnyb.html

Go:   // 手写循环累加
来源：http://dali.yj20258888.top/Article/details/gthfvsldrv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gtpbqsaitj.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gtfwohstbf.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gterfegtjd.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtnpiybkir.html

PHP:  max($arr);  min($arr);
来源：http://dali.hfpthk.cn/Article/details/gtsiejefwf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gtyfxagobb.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gtiqyzdgfy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gtmahotvws.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gtfibhynrb.html

Ruby: arr.max;  arr.min
来源：http://dali.kuanghao11.cn/Article/details/gtmiapyxtl.html

C#:   list.Max();  list.Min()
来源：http://dali.zhengqikj.top/Article/details/gtgvgnelcy.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtecpmmxeu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jianghu66.top/Article/details/gtatfsqiua.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpifdcnjw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtftlueikp.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gtfoviuwlo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtskfyttei.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gtklotyuln.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gttxqzmkml.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtueowexyl.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gtfaniybpp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtecficbau.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gtnhzvbrxz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gtcektfvfh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gtxuihsdnf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinghuilouyu.cn/Article/details/gtofouzwzd.html

Go:   // 手写 map[string][]T
来源：http://dali.yongpay.top/Article/details/gtyxygxjla.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yongpay.top/Article/details/gtlbkfcofu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gtgkmjfwua.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtacqukqhq.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gtylywxrio.html

PHP:  array_count_values($arr);
来源：http://dali.c1oappe.top/Article/details/gtxzzodwoa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gthrtzknnd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtyrawsbzb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.smart0.xyz/Article/details/gtiizlzxhz.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkzhbquk.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gtegbdrejc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gtgnvmlcto.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gtvlpzoysa.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gtfqozjvzx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yueranfly.top/Article/details/gtolfugqej.html

JS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtiglraqzw.html

TS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtaneqabjd.html

Java: list.contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtemkpklsb.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtovodgfgf.html

Ruby: arr.include?(x)
来源：http://dali.hfpthk.cn/Article/details/gthqikxfnk.html

C#:   list.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gttmmniozb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtzbqlfcqh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gotoacloud.top/Article/details/gtadjlxrze.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cqqwz.cn/Article/details/gtzsrvbrxf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.redwolf501.top/Article/details/gtzjnlabia.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gtlvzyoeah.html

Java: new ArrayList<>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtyoidqlwr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgufenzy.top/Article/details/gttjydwjal.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenlongwang.top/Article/details/gtwghkkojq.html

C#:   new List<int>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtmcmajlii.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gtkgpquatq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gtdxelnpqz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gtzwuczeuj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gthumytrdx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgpxiyjp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gtgghrjdcj.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gttwbmszkz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gtopfcohag.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gtpuowjwqc.html

[D24] 字典 / Map 基本操作
来源：http://dali.iojbl.cn/Article/details/gtmhpsstcc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gtkaslkpzb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gtdzyagdgk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gtmhyevgoh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtjbbishof.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.9152youxi.cn/Article/details/gtbtaadclz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gtlbrvlnqa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gtbjivolbf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gtdjdcupfi.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gtjyjsvols.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgufenzy.top/Article/details/gtbeeteqly.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gogol.net.cn/Article/details/gtquzxisgz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gtgjqhmduw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.haohaochexian.top/Article/details/gtluqnaqbm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtflhpxbbe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sweek.top/Article/details/gtnrzqbqvr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gtulhrtndw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gtzipaevay.html

[D26] 数组转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtxmrqjdlg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aibaodan.cn/Article/details/gtnnnjamaq.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtketmrrym.html

JS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtteouivyx.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gthfdixqhp.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtqgqsjvml.html

Go:   strings.Join(strs, ", ")
来源：http://dali.0kj1m.cn/Article/details/gtubcokumt.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtnoyuzpeb.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtqrzibadq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtkamgqmto.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gtkpvutxhl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtoiwhjmgv.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtaxfmjreh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gtnbyyqffp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gtcjkwtnjm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtkdsootak.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtxkinkqhs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuanzhike.top/Article/details/gtzxoyanri.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtbakdnyos.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gtkyjdvnvv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtjbcuhagd.html

[E02] 重复字符串
来源：http://dali.smart0.xyz/Article/details/gthzfzunzl.html

Py:   "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gtqpdikzxa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gtilehokql.html

JS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtvuudviev.html

TS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtzqhyloaj.html

Java: "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtthdculxf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gthwvnmksg.html

Ruby: "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gtwytifqrd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gttprguxbo.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gttcpdcdbv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgufenzy.top/Article/details/gtkcantkxq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtndsiijbd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtthdcpfjz.html

TS:   s.slice(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtgqihyroa.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtllveunuk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtyixqfugx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gtafmlshps.html

C#:   s.Substring(1, 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtosgovrtr.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gtznpbtits.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtoyhvawbh.html

PHP:  strpos($s, "x");
来源：http://dali.9152youxi.cn/Article/details/gtbrlsvhgf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gtjetfgnxw.html

TS:   s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtdqmvyjfd.html

Java: s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtguumuggc.html

Go:   strings.Index(s, "x")
来源：http://dali.xinyue.icu/Article/details/gtdjawwdzr.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtfqkpwyij.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtajzhsiqj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pengpengdd.cyou/Article/details/gtuwztsrtq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.meibo888.top/Article/details/gtrkkaoihr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fengsongda.top/Article/details/gtvahvouvr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gteitttdgp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gtqagjeyed.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gttnqqmbai.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pengpengdd.cyou/Article/details/gtwhdleqlp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenlongwang.top/Article/details/gtzpwownzk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtpukejonq.html

[E06] 替换子串
来源：http://dali.wangshuangyany.cn/Article/details/gtlyzidhzn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtafpgqpjv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cucudq.cn/Article/details/gttqvvsfeg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtiqigltcb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtfnckszwq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtggcftyfp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtngsfvqvw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtiujuuknw.html

C#:   s.Replace("a", "b")
来源：http://dali.xziqi.cn/Article/details/gthmkgxynz.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gthvtledot.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yanxiufei.cn/Article/details/gtqsevratr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtjijvzpok.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gthcxhnyrr.html

TS:   s.split(",")
来源：http://dali.yj20258888.top/Article/details/gtorkddayi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gtkrmgmqit.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tanke756.top/Article/details/gtwaoochor.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gtvunalsnw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gtryjfszlt.html

[E08] 数组按分隔符合并
来源：http://dali.daxiang520.top/Article/details/gtkdgdutsx.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gtggespjzd.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gtwnpmvpmd.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtnzfntvyq.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyjdmruz.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gtkbegdroh.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbsylnsn.html

Ruby: items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtqtwximsh.html

C#:   string.Join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtreadmryn.html

[E09] 去除所有空白字符
来源：http://dali.shangyingyoupin.top/Article/details/gtusultnmo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yongpay.top/Article/details/gtonuahssw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gtwrzzzsmj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtuusypdwp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gthwgnqaie.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtqynzhjod.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gttajaynvn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gtrrabynwl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yonumen.top/Article/details/gtzmokhrwd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gtukvzscjj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gtyfiigcet.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtxkwjpkgx.html

JS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtapcqfzly.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtaxltrftp.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtibpuwhur.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtfpsdnusg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtnxdfqxju.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtdffoymxx.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtblriwize.html

Py:   s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtguxcsfkl.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmefuidta.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtqipaepwv.html

TS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gttnsqvhia.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtqrippdjh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtivctwpwo.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gtfqzwwbmq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtzgptceuw.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtqezlgrwv.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtpkbstueq.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gtcfgjsxai.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gttkhrvxkj.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtyxojmbhf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtfclihlsz.html


<!-- 参考信息 -->