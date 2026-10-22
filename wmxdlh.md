代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnxiangtu.top/Article/details/gtwxzglyhg.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gtuunzmzzv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtypkwpmrp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gogol.net.cn/Article/details/gtnjrkbdfr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zdqjudy.top/Article/details/gtzhjifzdr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gtppqgpsrh.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gtslazkxtx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtudvbjtuh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtlastdljx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxleffkl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shangyingyoupin.top/Article/details/gtkrtfzdmo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfefomxx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtdembbnbf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtaddomkwu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtukptxuym.html

[D06] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtjjplhikh.html

Py:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtiexgqhhx.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtdlqshbmw.html

JS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtzwtzyldi.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gtvhjxbhht.html

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gtqsffhiwf.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtvapshzwe.html

Ruby: arr.length; arr.size
来源：http://dali.zhengqikj.top/Article/details/gtbsqdlaqq.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gtotkpxtgz.html

[D07] 切片 / 取子数组
来源：http://dali.ydzc1.top/Article/details/gttiocolvc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gtyaiykvda.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gtpomycibd.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtqtxnwwod.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtstsdupdt.html

Java: list.subList(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtfdofflki.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gtncefyhgm.html

Ruby: arr[1, 3]
来源：http://dali.fzhhl.top/Article/details/gtwrcoymtj.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtrlfdksbo.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gtsvkyoyys.html

Py:   a + b;  a.extend(b)
来源：http://dali.iojbl.cn/Article/details/gtktmnnhuo.html

PHP:  array_merge($a, $b);
来源：http://dali.zhoulong.xyz/Article/details/gtzoaoialg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gtzvukmrbg.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpjyzymj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqqgrglp.html

Go:   append(a, b...)
来源：http://dali.hongshengwenyu.top/Article/details/gtepmphzsx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ivvv.top/Article/details/gtbtcxxhdx.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtvonfhxoq.html

[D09] 排序（升序）
来源：http://dali.wangdashe.top/Article/details/gtigxeduss.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtbfvrekdm.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gtsnlgbrkc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gtpthigbki.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cashguo.top/Article/details/gtseewpxoy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhiwuduotai.top/Article/details/gtidrrxbvp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtcnqxhhyd.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtsrjmtrhp.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gtpqovotxd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtlsnxiyyq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sxryk.cn/Article/details/gtbsjpuhia.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtptfjozoa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtujumedrh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtscbpsbsw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuanzhike.top/Article/details/gttrvqreqb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gtuhjnlvpe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gtwrrnxtgv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hongshengwenyu.top/Article/details/gtzlblapui.html

[D11] 反转数组
来源：http://dali.shangyingyoupin.top/Article/details/gtnxnvougw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gtvqlistcj.html

PHP:  array_reverse($arr);
来源：http://dali.hnqzz.top/Article/details/gtkiwisrfe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gtztnnkozm.html

TS:   [...arr].reverse();
来源：http://dali.aizwys.cn/Article/details/gthzqqpomw.html

Java: Collections.reverse(list);
来源：http://dali.yvedp.cn/Article/details/gtbexpjlht.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gtpbbzfxft.html

Ruby: arr.reverse
来源：http://dali.iojbl.cn/Article/details/gtyfhzzdfk.html

C#:   list.Reverse();
来源：http://dali.ybcxt.top/Article/details/gtwbmauhnp.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gtazunavar.html

Py:   arr.index(x);  x in arr
来源：http://dali.birdmap.top/Article/details/gtuaiplncm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gthyuuobzf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtwwuqknek.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtcsyktjjo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gtlgrbyqla.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtcyprpobr.html

Ruby: arr.index(x)
来源：http://dali.jinqigfzy.top/Article/details/gtjqugqqks.html

C#:   list.IndexOf(x);
来源：http://dali.nanxinkj.top/Article/details/gttfovxjbg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gtoukrdqks.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dianchejie.cn/Article/details/gtoxpkpoci.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gtwzkhhrqk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtjcjdytli.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtvlpyqbwh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.mhx1999.top/Article/details/gtgognmmbn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmaescjz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.9152youxi.cn/Article/details/gtzatlvsqy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtwihmfmto.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuetiantiany.cn/Article/details/gtbuhsfipk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tian-w.cn/Article/details/gtgoaloxbt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtcqmhjijn.html

JS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtlsudnaen.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtzkmhbebf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtyjctqmhw.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gthaxnecwn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yvedp.cn/Article/details/gthoghepmh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtnfnxwldb.html

[D15] 去重
来源：http://dali.birdmap.top/Article/details/gtbjxxqcsu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gtfawsbzot.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvipfhts.html

JS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtpqpnpejk.html

TS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcorvojqs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gtnyakaqax.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinghuilouyu.cn/Article/details/gtczpjqvuv.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gttahxpezd.html

C#:   list.Distinct().ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfmledtt.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gtsczextsb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tanke756.top/Article/details/gtitavuwjn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigufen.top/Article/details/gtxjvijfgh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtrieueazu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtqwyvuxbo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gtnuboabyq.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gtbspnlvne.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtziwwocac.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gtdvmcegmk.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnjpnvjy.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gtzmhwsnnb.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gtwccxsxpv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gtlxualwdt.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gtubcylgxo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nwbrower.top/Article/details/gtueisyhdk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuanzx.com/Article/details/gtaqwzeuem.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gtujeqnnkb.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gttibmfddw.html

[D18] 扁平化嵌套数组
来源：http://dali.tian-w.cn/Article/details/gtfwnzstet.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gtgzlzqpie.html

PHP:  array_merge(...$nested);
来源：http://dali.feifeiyinyue.top/Article/details/gtyztfieaj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gtfnyzivms.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gttzwwqlrj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shuidangran.top/Article/details/gtxfjdiimo.html

Go:   // 手写双层循环
来源：http://dali.nanxinkj.top/Article/details/gtncfriquo.html

Ruby: nested.flatten
来源：http://dali.feifeiyinyue.top/Article/details/gttqzhihzb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gtjsjbfwbd.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gtudrrcbqa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.snrcjt.cn/Article/details/gtpeqnhfvn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgufenzy.top/Article/details/gtfrdikgcq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtjcppmvxx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtswbqbhzw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtdsgywdgz.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gtlqvjnwnj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqhocbao.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.havefunace.top/Article/details/gtqzaogfct.html

[D20] 统计每个元素出现次数
来源：http://dali.tanke756.top/Article/details/gtnhedpbje.html

Py:   Counter(arr)
来源：http://dali.snrcjt.cn/Article/details/gtqvhwbosh.html

PHP:  array_count_values($arr);
来源：http://dali.yangfankeji.com/Article/details/gtmygpmsrf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtdmcctibw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtokasocyh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyenrwkde.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gtazcuvmie.html

Ruby: arr.tally
来源：http://dali.daria6918.cn/Article/details/gtgzqisaaz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gtcdvixqjv.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtoljkjnkp.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtbfdhqcsi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkxwbijg.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtyybficji.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwifvtjlg.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtbztulybi.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtbrixkmle.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gtmzspakls.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtmcxxhelh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gttwmtoskk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtqylylwuw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pengpengdd.cyou/Article/details/gttciljmka.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gtpefcoazd.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtlotrrffx.html

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gtlbohuzxy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtcfaikycv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gtoifnbxgm.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gtudrkzltc.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gtyygtogpl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlneryirl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsptjzsfc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtwjiwbqqy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtkuifnbao.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gtbsnxpyce.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtzvmklyob.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.bjfxy.top/Article/details/gtbowdjcab.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gtwhltyeip.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxinkj.top/Article/details/gtevmjpqty.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.snrcjt.cn/Article/details/gthpigvgdq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuiorggh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtjtzummmp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtybnfbyqn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpfujrph.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guowangkeji.top/Article/details/gtttylspwd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dashuyun.cn/Article/details/gtvxewesvp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtldpblvnp.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpvwrinj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtnwprntnk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtpoviulap.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyssxnfj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gtvlyzkjfv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gtohlqcuco.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gtalzsxpij.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cucudq.cn/Article/details/gtesoantpg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gtlgjbeoho.html

[D26] 数组转字符串
来源：http://dali.ivvv.top/Article/details/gtpuxzpgdc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtnpcmadcs.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtgscvfbkg.html

JS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtoayeamaj.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtmuxqmfdi.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtgsfbblyc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmzorfke.html

Ruby: arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtolxfmgbk.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gtwfyzafwe.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfijdwqsu.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gtedjqaouq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkaojcfi.html

[E01] 拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtcpofurlh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gtxpyftpaq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gtxcukhpit.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gttubsvtcr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtgogwyvzw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gtlyeoaikq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtscafikrg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.svipenyu.cn/Article/details/gttubsgthw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtkyvsjqbp.html

[E02] 重复字符串
来源：http://dali.c1oappe.top/Article/details/gttdyjntip.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gtmczbtfkx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ivvv.top/Article/details/gtyekoexhh.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtakmljahh.html

TS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtocvskdsr.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtrystvfhj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gtqjyoqrkp.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gttolpwpeh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yanxiufei.cn/Article/details/gtdkrwhwpw.html

[E03] 截取子串
来源：http://dali.birdmap.top/Article/details/gtgyrabdju.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gtfcjgauwr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtpenecgjr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtjvyfxplx.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtrwzutqyv.html

Java: s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtarybkkrb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gtiyzppwnz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daria6918.cn/Article/details/gtnzevlaux.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gthihqkxxf.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gtqzlazqnv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtogknzuks.html

PHP:  strpos($s, "x");
来源：http://dali.0kj1m.cn/Article/details/gtijgflurk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gtepyexlmz.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtydjitigt.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtkgvrhguy.html

Go:   strings.Index(s, "x")
来源：http://dali.shangyingyoupin.top/Article/details/gtrjlxmsjq.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhpbiatx.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtmunyscyg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yueranfly.top/Article/details/gtlmojvize.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhixingplan.top/Article/details/gtevtpkuir.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmptzglo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtnkluhvht.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gtfrjaofta.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtgoliptdm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gthtnmnkzi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnugaavcw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtsozsfrfr.html

[E06] 替换子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsikxzyh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtymklmbfy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangdashe.top/Article/details/gtbkvfqivk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtxjsaqwto.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gttylpizzr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtsmiwxbvl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtocmxflby.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtfgadpcej.html

C#:   s.Replace("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtkwhfesht.html

[E07] 按分隔符拆分
来源：http://dali.zhengqikj.top/Article/details/gtbcdzedtl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xylfe.cn/Article/details/gtiutvhezn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtcuckpjsl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafhbwttc.html

TS:   s.split(",")
来源：http://dali.c1oappe.top/Article/details/gtcpkeblge.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gtetcfkzix.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenzaomai.com/Article/details/gtobfmesyx.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gtouylkxvt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.meibo888.top/Article/details/gtalesupkd.html

[E08] 数组按分隔符合并
来源：http://dali.yuanzhike.top/Article/details/gtywokwcmo.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gtgayqcezs.html

PHP:  implode(",", $items);
来源：http://dali.andypj.xyz/Article/details/gtsyccwqfz.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtclqssugs.html

TS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtkuqlrygo.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtmmvvukux.html

Go:   strings.Join(items, ",")
来源：http://dali.mhx1999.top/Article/details/gtzpvghuyz.html

Ruby: items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtbafdgxdq.html

C#:   string.Join(",", items)
来源：http://dali.redwolf501.top/Article/details/gtpegdmehl.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gthjsaqdft.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqmdibzq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.c1oappe.top/Article/details/gtkimabosz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhvusvec.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtfduzxlvz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.smart0.xyz/Article/details/gteepweaox.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hysaishi.cn/Article/details/gtdxzmtznf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gttfoylajc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtpwsqiedx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gtqngjdqbg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cashguo.top/Article/details/gtbofjjbqc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gteysxepoz.html

JS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gthwljkwot.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtbxwbbztw.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtnivhwuws.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtypndgtud.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtmtvhalwp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gtjkpgkhdx.html

[E11] 反转字符串
来源：http://dali.9152youxi.cn/Article/details/gtjznjlaav.html

Py:   s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpatrdrsf.html

PHP:  strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gtdoklzmjs.html


<!-- 参考信息 -->