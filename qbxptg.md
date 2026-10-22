代发 wailian999

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtceumwlnv.html

[D04] 删除元素
来源：http://dali.wangdashe.top/Article/details/gtmstcqaob.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gtkgvtccia.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xziqi.cn/Article/details/gtizffcnyw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gtwcntzkar.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gtvligxrbd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cheryme.top/Article/details/gtyjoplpgd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenjidiqi.icu/Article/details/gtjzkyafpp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jianghu66.top/Article/details/gtlegjsmbu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.vqdsnc.cn/Article/details/gthaydcmuq.html

[D05] 访问与修改元素
来源：http://dali.ybcxt.top/Article/details/gtrdschtsm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtzaxlcafw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtclkaooxa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gthufmttxt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gtlxrujvdc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gtzkeinkap.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtmwuwipip.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtvfmuvfdb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtphzkqfkj.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtjpupqtuq.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtbviscbhp.html

PHP:  count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtjcolnilo.html

JS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtzltgjhfx.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtxpnccnaf.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gtxseuzpzi.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhvtdhio.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gtpwvotmtf.html

C#:   list.Count;
来源：http://dali.guannengcc.top/Article/details/gtdpzxmiin.html

[D07] 切片 / 取子数组
来源：http://dali.aizwys.cn/Article/details/gtgobnhkmn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gtyzjazygb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gtfhnurddg.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtwkwqwngs.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtdrwetvcv.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtmkxgieqh.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gtxcayebwc.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxfosctx.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtumkolsvr.html

[D08] 合并两个数组
来源：http://dali.pycfn.com/Article/details/gtklxjowjd.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gtydydujgq.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gtqedtdjhk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gtengmdakq.html

TS:   [...a, ...b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqsxsohy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gtxbkuwezk.html

Go:   append(a, b...)
来源：http://dali.0kj1m.cn/Article/details/gtcsyvgkpj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.quarkkingdee.top/Article/details/gtklzrxshn.html

C#:   a.Concat(b).ToList()
来源：http://dali.316326.xyz/Article/details/gthkpgvyeg.html

[D09] 排序（升序）
来源：http://dali.hongshengwenyu.top/Article/details/gtvkgdrxxy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtrlfpbzic.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtmzciqvwx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhixingplan.top/Article/details/gtuhjajeze.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gtyqswugex.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gtbokymyov.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtycdttvxb.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtrkptrfii.html

C#:   list.Sort();
来源：http://dali.0kj1m.cn/Article/details/gtycshnrck.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigufen.top/Article/details/gtiqlvvpin.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gttqbuntpl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gtvtvjrsei.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtspeeupbw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtmzhaphde.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cdnleiting.top/Article/details/gtktxsnfuh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gtecialieb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.birdmap.top/Article/details/gtscggjwjp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.iojbl.cn/Article/details/gtpjjvdoqp.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtqbpjpeku.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqbkvptw.html

PHP:  array_reverse($arr);
来源：http://dali.yj202588.top/Article/details/gttevqtyto.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxinkj.top/Article/details/gtensobtlt.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gtpriwplda.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtccaknbhj.html

Go:   slices.Reverse(arr)
来源：http://dali.wangdashe.top/Article/details/gtcqnzoxom.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtxmkglkwx.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaenebqqk.html

[D12] 查找元素下标
来源：http://dali.shzxlz.cn/Article/details/gtppgcpqfm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqdbqytt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtfgrhsplr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtswebfuid.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtbqcihfxc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ybcxt.top/Article/details/gtyeyinokp.html

Go:   slices.Index(arr, x)
来源：http://dali.316326.xyz/Article/details/gtzclzevya.html

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtewnksvcd.html

C#:   list.IndexOf(x);
来源：http://dali.sufxvd.cn/Article/details/gtwqczhhxh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gtdfunexec.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xinyue.icu/Article/details/gtirpzmghi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cdnleiting.top/Article/details/gtxmqxwzxd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtbldudbvx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtfostdjuu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gtzdgnakdu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gtaavdfapc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gtpotutakg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtpprnmndq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywutzniq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtkdifknoz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gtswaxdwdb.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtlrxisuso.html

TS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtaouydojz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shuidangran.top/Article/details/gtvlrryias.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtvlnwpnvf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gttdyqkvfr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtiqipkevl.html

[D15] 去重
来源：http://dali.0kj1m.cn/Article/details/gtuajarqbf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtmxbugfpm.html

PHP:  array_unique($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnoqtnal.html

JS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtwpzvamrg.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtdtgytxgg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gtzovjjcnk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gtqbjoxncm.html

Ruby: arr.uniq
来源：http://dali.mhx1999.top/Article/details/gtibrosldf.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gtuvsngjvs.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gtqbixchtx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xinyue.icu/Article/details/gtomoiycup.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxisyeeso.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtvjrskyzm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtoewradqc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.c1oappe.top/Article/details/gtfenkvjpm.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gtoyiysrnt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gtqqmzipfe.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gtvxwwfhkb.html

[D17] 最大值与最小值
来源：http://dali.redwolf501.top/Article/details/gtmvrhtvpm.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtloovbsal.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtcmoepgny.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtepofgyhm.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtxhhfhfxw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gtmkfcdecp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gtsatjtjhs.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gthefxxdbj.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gtjgtcntpm.html

[D18] 扁平化嵌套数组
来源：http://dali.gaohongyu789.top/Article/details/gtgnopklad.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gthzkykvwr.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gtnfokqvlw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gtgahfqljx.html

TS:   nested.flat();
来源：http://dali.0kj1m.cn/Article/details/gtnuweusvl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gtlrrvzibz.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gtibwhuocp.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gttkyuttoq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.meibo888.top/Article/details/gtshondypv.html

[D19] 按字段分组
来源：http://dali.haohaochexian.top/Article/details/gtbglykzms.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhixingplan.top/Article/details/gtumnkgdqq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gogol.net.cn/Article/details/gtsszxpbdz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gtpxyrkexh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtfdnkzmmp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shangyingyoupin.top/Article/details/gtymzbdpts.html

Go:   // 手写 map[string][]T
来源：http://dali.hnqzz.top/Article/details/gtzoyrxilf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.smart0.xyz/Article/details/gtosampyqc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.c1oappe.top/Article/details/gtgdnvzgeu.html

[D20] 统计每个元素出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gtsmbwgknt.html

Py:   Counter(arr)
来源：http://dali.yvedp.cn/Article/details/gtdyahopoi.html

PHP:  array_count_values($arr);
来源：http://dali.ydzc1.top/Article/details/gtwyyxasba.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gtbhzcbnqa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gtfwleclyb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gtncfqyyla.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gtllzlndlk.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gtmorcyvnn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gtknymdjav.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gtibsyblmm.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gtuktnwzof.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtciateiat.html

JS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmtpjvhf.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtyrzyvxkw.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gtpviqembq.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtmfmgieik.html

Ruby: arr.include?(x)
来源：http://dali.sweek.top/Article/details/gtjbbrrdjl.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucebucat.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gtzfqcuupj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwtsagxj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ehwqpu.com/Article/details/gtefnivgww.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gtewdwvpsb.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gtmiypuhyw.html

Java: new ArrayList<>(list);
来源：http://dali.9152youxi.cn/Article/details/gtxbpxxmdh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gtnwebjaik.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gtvzeizaku.html

C#:   new List<int>(list);
来源：http://dali.jinqigufen.top/Article/details/gtuapggesl.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtoepzbban.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtfplqgjvf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gtnshnsmzs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gtsmaccfhn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gthsmalzql.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.havefunace.top/Article/details/gtgidllfny.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gttdjlkece.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gaohongyu789.top/Article/details/gtietgyxfj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gteeqirxur.html

[D24] 字典 / Map 基本操作
来源：http://dali.yongpay.top/Article/details/gtlvkyppav.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gtdwideuok.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gtptnsuyth.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtabzzwtft.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtdrdbgsls.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gtfgwpaykz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gtebpbimhq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gtcmkfdkwq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gtksfqrdiz.html

[D25] Set 集合去重与交并差
来源：http://dali.quarkkingdee.top/Article/details/gtgkimkvxd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gtaklzubuc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gtkubcqcpk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ivvv.top/Article/details/gtdwgfgkzi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shuidangran.top/Article/details/gtdhhcohxd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gteijiljxi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sxryk.cn/Article/details/gtlbvvugsw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gtdjbzepgf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtiaeqqhms.html

[D26] 数组转字符串
来源：http://dali.aibaodan.cn/Article/details/gtohxwfdmk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aibaodan.cn/Article/details/gtwnsxccqa.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gtytvtrtzp.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtqajfople.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtdfdmhfnu.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtnufqkwkc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gtjgrbxefb.html

Ruby: arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtmyyakvjn.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtemsbbnca.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtlgwyejvw.html

E. 字符串处理
来源：http://dali.ehwqpu.com/Article/details/gtlijxngbk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtodplfjky.html

[E01] 拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtbahsqhgl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenlongwang.top/Article/details/gtjvfmebjk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gtznaqvecj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtcahrxwci.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtgvhxbbat.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zycfv.cn/Article/details/gtbxszzlwb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gtohpzklsk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxuanxn.top/Article/details/gteuzkdcsy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xylfe.cn/Article/details/gttzlderhu.html

[E02] 重复字符串
来源：http://dali.chenzaomai.com/Article/details/gtercyorjf.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtzxklgtjp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gtvqxazhpw.html

JS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gthylymmrh.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gttmsqvoub.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtttkopwsz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtmklawqic.html

Ruby: "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtyihzgbem.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.haohaochexian.top/Article/details/gtmdphxnkj.html

[E03] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtpyumwwfp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sufxvd.cn/Article/details/gtuducygmp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsviypgk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtrwijdpyv.html

TS:   s.slice(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtatohanxk.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtyoqchymq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gtxjjpzszf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gttounsjjz.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigfzy.top/Article/details/gthqgdovha.html

[E04] 查找子串位置
来源：http://dali.tianlin.xyz/Article/details/gtzeiobdhc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtqgajsyev.html

PHP:  strpos($s, "x");
来源：http://dali.smart0.xyz/Article/details/gteqjuoukl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fengsongda.top/Article/details/gteyghfkcy.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtmufucuzx.html

Java: s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtiibyjdew.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gtqevceyxg.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmscczdwa.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtnovgzwda.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dashuyun.cn/Article/details/gtmigfbmtc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtpjexzdme.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthuorwgsy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtcnoutvlf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gtqczohtvo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtpsqsbwmq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.snrcjt.cn/Article/details/gtfxrxbnnc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pycfn.com/Article/details/gtpsqkxklu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtrelsihao.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gtergvryoo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtlmipovpb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtbctwthxp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtlzzhmnbu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gthdvwznic.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtatfuewgq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gtaykzcfnh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtywfshawb.html

C#:   s.Replace("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtcdakfomy.html

[E07] 按分隔符拆分
来源：http://dali.jinqigfzy.top/Article/details/gtctvzwxbg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gtamircczi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtsbyuszwd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtuuggawtk.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gtklbgjiii.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gtywvixatm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gtvcfpvret.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gtiupypnsl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gtrjqkpnui.html

[E08] 数组按分隔符合并
来源：http://dali.hfpthk.cn/Article/details/gtjgctblia.html

Py:   ",".join(items)
来源：http://dali.zycfv.cn/Article/details/gtwrwxcjzk.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gttvxdqqgm.html

JS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtzkefhiad.html

TS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtqapwmqje.html

Java: String.join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtfxvasjdu.html

Go:   strings.Join(items, ",")
来源：http://dali.meibo888.top/Article/details/gttuionmjj.html

Ruby: items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtteimmpzw.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtlzgvktsg.html

[E09] 去除所有空白字符
来源：http://dali.zycfv.cn/Article/details/gtovasmsuq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gtrbxtiahp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cheryme.top/Article/details/gtatcxapkc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gtotswqlgm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtsgwosmdh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtcfvqfrtf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gthdqhhswi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gthubreced.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtffltqdcs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hywenlv.cn/Article/details/gtikrcwqnc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtfcrffwnq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gtpncjlcbn.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyyznjen.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtgxlvlpsz.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtfyexcunc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gttihosztg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtfopebcxr.html


<!-- 参考信息 -->