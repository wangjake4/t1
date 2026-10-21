代发 wailian999

[D03] 在指定位置插入元素
来源：http://dali.zhoulong.xyz/Article/details/gtcimhkllm.html

Py:   arr.insert(0, 0)
来源：http://dali.yvedp.cn/Article/details/gtvnmcjjwm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gtpjcvtkkj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.316326.xyz/Article/details/gtvmjpcvkz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtmgqatcfm.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgruhqwwg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaipxstlh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jyoumei.cn/Article/details/gtditsnece.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtameradqh.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gtapkzmioy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yanxiufei.cn/Article/details/gtoqascprm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hywenlv.cn/Article/details/gtozyevjav.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shangyingyoupin.top/Article/details/gtkwjhlyvl.html

TS:   arr.splice(0, 1);
来源：http://dali.ppjwa.cn/Article/details/gtumumwyki.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jlsjyb.cn/Article/details/gtjqzviked.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtejwtzkzk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guowangkeji.top/Article/details/gtihclsxgg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.vqdsnc.cn/Article/details/gtsfdhpyfl.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gtcemjxgqg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtszxfryza.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtyvnaypkg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtchigbzle.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gtnizpxoki.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gtpehifsgl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtrnnzxhgq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtcidqcqxj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtmqdptyir.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gttlxlorzy.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtsxhbfibc.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gtypzmgrfm.html

JS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gtfpeidnot.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gterhyfrlh.html

Java: list.size();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsvugkzo.html

Go:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gtsutsqpge.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gteqrelfky.html

C#:   list.Count;
来源：http://dali.pengpengdd.cyou/Article/details/gtodqvklow.html

[D07] 切片 / 取子数组
来源：http://dali.hammf.cn/Article/details/gtjgxtfkej.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinghuilouyu.cn/Article/details/gtaufftkoz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtyfblnbtv.html

JS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtngwekznt.html

TS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtrgxnnfkg.html

Java: list.subList(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtklzafsth.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gtuhqeopdv.html

Ruby: arr[1, 3]
来源：http://dali.yuanzhike.top/Article/details/gtzgqzbmeh.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtryrirgsi.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gtekpivtnx.html

Py:   a + b;  a.extend(b)
来源：http://dali.jianghu66.top/Article/details/gtputtfbhr.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gtzgmekzqw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ydzc1.top/Article/details/gtvwyffnkz.html

TS:   [...a, ...b];
来源：http://dali.yanxiufei.cn/Article/details/gttggfpzfb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gotoacloud.top/Article/details/gtccdeuner.html

Go:   append(a, b...)
来源：http://dali.pengpengdd.cyou/Article/details/gtgzmelbru.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gtixkihvaw.html

C#:   a.Concat(b).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtsnsymbnh.html

[D09] 排序（升序）
来源：http://dali.andypj.xyz/Article/details/gtcnsnsibk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtpdnvkfdl.html

PHP:  sort($arr);
来源：http://dali.hfpthk.cn/Article/details/gtdhirmztr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gtclekgotp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gtwaezvgeg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ppjwa.cn/Article/details/gtrigwtive.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtfvscrchc.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtegrdoail.html

C#:   list.Sort();
来源：http://dali.daxiang520.top/Article/details/gteanyhsut.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guowangkeji.top/Article/details/gtyscjckzl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucvagznt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gtfbmsgcfc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtstcrgrmj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtpakfmqjm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangshuangyany.cn/Article/details/gttjhiqkox.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gtlqbubehm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gtxpicawrd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigufen.top/Article/details/gttssxpzth.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gttiytpmpk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gtcyoyyjfw.html

PHP:  array_reverse($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtcvnjrvkx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gthxyessum.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gtygiwbkcn.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gtmoyzdsrm.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gtcjimrmrm.html

Ruby: arr.reverse
来源：http://dali.mhx1999.top/Article/details/gtzqpkxipm.html

C#:   list.Reverse();
来源：http://dali.nwbrower.top/Article/details/gtoykwgjia.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gtpbibsyyd.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gtqnpkscat.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cheryme.top/Article/details/gtwgepomsl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtfjmabicv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtcoaxyebt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gtinjcqgeh.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtprlpnqed.html

Ruby: arr.index(x)
来源：http://dali.wangdashe.top/Article/details/gtrsysxpjd.html

C#:   list.IndexOf(x);
来源：http://dali.gogol.net.cn/Article/details/gtewufnfir.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gtatblythk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gtxligdfit.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.316326.xyz/Article/details/gtoxeasnhm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtgmkqrwvi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtswbluqnj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gtunnlunpt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gtysvrhepx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gteitnzlvt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrddrchea.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gtdvjzwcnu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtplrdhsbh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtniqmuesz.html

JS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gtmssfkjwi.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtcsdzbpat.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtikycyryw.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gtmibmvosc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtchkdpgqe.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtgkcebfpq.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gtkbjfcorm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtvwojeleh.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtccgpmcxv.html

JS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtnxtpfllm.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtqrwzmmbt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnxiangtu.top/Article/details/gtimjkmgyx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gtertqpcct.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gtauzzbrqd.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gtjgyvpusy.html

[D16] 求和与平均值
来源：http://dali.svipenyu.cn/Article/details/gtqcudksvi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnoqcizj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gtqdrwbxbg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtmhqpqget.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtsokfumwe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gtctfwratk.html

Go:   // 手写循环累加
来源：http://dali.shuidangran.top/Article/details/gtjfrvtakh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guowangkeji.top/Article/details/gtkofnqbvi.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258888.top/Article/details/gtvlnqhbod.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gtbcjxyoov.html

Py:   max(arr);  min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtlxadsrwb.html

PHP:  max($arr);  min($arr);
来源：http://dali.guannengcc.top/Article/details/gtojrvwikx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gtrpxucerz.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugsdusgr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.c1oappe.top/Article/details/gtagvxyetg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.birdmap.top/Article/details/gtwukxoxlv.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gtekuzugng.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gthisikpts.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gtsfguxvpg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.redwolf501.top/Article/details/gtccwgftvw.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gttgoxvfdm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gtejnjdgkg.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gtllniiivi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shzxlz.cn/Article/details/gtgdbxfekh.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gtokkiivoh.html

Ruby: nested.flatten
来源：http://dali.jinghuilouyu.cn/Article/details/gttxwtakkq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.andypj.xyz/Article/details/gtxoexjvzg.html

[D19] 按字段分组
来源：http://dali.0kj1m.cn/Article/details/gtrrxapzhg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.svipenyu.cn/Article/details/gtsgkzkeet.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hongshengwenyu.top/Article/details/gtrmmsmlsh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cheryme.top/Article/details/gtttaxwebb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gthfenxjin.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gtgjufioub.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gtxmpleyme.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gtrrnmglrd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gthjbvktyp.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtijpttggf.html

Py:   Counter(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtazsuomxm.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gtwfoytkhc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtpjsgilap.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtigdabcix.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gtjsvtxoyt.html

Go:   // 手写 map[T]int
来源：http://dali.nwbrower.top/Article/details/gtudmgndds.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gtwewmfahf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gtiinwhqtj.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigfzy.top/Article/details/gtaaeyeawa.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gtkltxevhv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gtrgzstjfo.html

JS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtciilfqzl.html

TS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtsdypminp.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtafpibyyy.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtuyafgghe.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtynllebdo.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gtnmdwgbbd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gtgrgbaznt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gtnghcemfk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhixingplan.top/Article/details/gtrmvhgxsd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gtuzcpaild.html

TS:   [...arr];
来源：http://dali.feifeiyinyue.top/Article/details/gtzfdghoku.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzczwigrj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgktsowng.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gtlpnoealh.html

C#:   new List<int>(list);
来源：http://dali.hammf.cn/Article/details/gtmpsvamis.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gtzcztiebw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gtguyflmtn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtwaxcmrze.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtbnukcpck.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtwjsptspa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangdashe.top/Article/details/gttkdgooeb.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtvxtszcpo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tian-w.cn/Article/details/gtgydatmqi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gtvclsbmmp.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtbdtajbja.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gtnhuvzrla.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gtvprvdyuw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtivqquxvt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtwljtalom.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hammf.cn/Article/details/gtfmxcqdmb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gtzywvdszu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtxuarzpmn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gtoujrzmah.html

[D25] Set 集合去重与交并差
来源：http://dali.jiagoushi.top/Article/details/gtdnasfdid.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tian-w.cn/Article/details/gtvnccljvo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gtqkhcmxps.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gtmzleaxyt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.iojbl.cn/Article/details/gtbflzyayg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gtjtpezffj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sweek.top/Article/details/gttzpigbgm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtryysiepj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbykbeefu.html

[D26] 数组转字符串
来源：http://dali.dianchejie.cn/Article/details/gtueqbyfwt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gttzeyqalt.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtinpsooep.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtojzmvtjt.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtecgqsswk.html

Java: String.join(", ", list)
来源：http://dali.yj20258.top/Article/details/gtzdfirpbc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gtpjsqblvw.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtyjzpwepp.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtvlfelmsv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtyturbuad.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gttkfmtakq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtoyupzgif.html

[E01] 拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtjnvfamdd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gtybjhpijl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cheryme.top/Article/details/gtlxmvtann.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gtzjlwwslv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtervxegyi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gtsdpytyrj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gtkexxwyei.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gtefesktvf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtshpiogbk.html

[E02] 重复字符串
来源：http://dali.xuanzx.com/Article/details/gtmxenxiyz.html

Py:   "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gthyruxlzr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zdqjudy.top/Article/details/gtakhdiksf.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrljkamw.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtiwlnpvku.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtlyeqluru.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenlongwang.top/Article/details/gtoolikxaw.html

Ruby: "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtvykedwku.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.haohaochexian.top/Article/details/gtocppiqng.html

[E03] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtnlimuzfs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gtqbxvejma.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntutmufq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtiqgcgamu.html

TS:   s.slice(1, 4)
来源：http://dali.sweek.top/Article/details/gtrhbsvumm.html

Java: s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtlbtgolyu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtczamdmfy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenjidiqi.icu/Article/details/gtnwiqjpur.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258.top/Article/details/gtxptlplmv.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gtdmwvxxlq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pycfn.com/Article/details/gtzzadxban.html

PHP:  strpos($s, "x");
来源：http://dali.hnqzz.top/Article/details/gtzphbniyy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cashguo.top/Article/details/gtxytwvbvf.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtuztkvnwu.html

Java: s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtbnrphwpd.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gtojelymvx.html

Ruby: s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtfodyzbsu.html

C#:   s.IndexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtyyvrklih.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.haohaochexian.top/Article/details/gtjokdlduk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtdkzqncuh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gtrnmuzwut.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gteunfqgfe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.snrcjt.cn/Article/details/gtmztqoccz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtizvlmqvb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxuanxn.top/Article/details/gtftsrkloy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gtewsngyrl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtuzxxaicy.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gtcfmngsdz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntbhrudi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gtrbugwspc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybjzjhbr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtlgaxiwrc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrxgtmtk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gtsgwvabby.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtawwfrpwc.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtfemotept.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gtpbrhjrgp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gtofthljim.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtrhhnychw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuxming.cn/Article/details/gthjlfdxqu.html

TS:   s.split(",")
来源：http://dali.zhixingplan.top/Article/details/gtmwcbqmuh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenzaomai.com/Article/details/gtoqwfaawj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.haohaochexian.top/Article/details/gtstxgzzrt.html

Ruby: s.split(",");  s.split
来源：http://dali.pengpengdd.cyou/Article/details/gtpldurllz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhiwuduotai.top/Article/details/gtmsrsuqvv.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gttniptbpv.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gtpqbnvuxp.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gtmiieiejf.html

JS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirnebrve.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzobqgnzc.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtywtzsnxn.html

Go:   strings.Join(items, ",")
来源：http://dali.svipenyu.cn/Article/details/gtwtfsyvwq.html

Ruby: items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtxgcoznrq.html

C#:   string.Join(",", items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwfwqtke.html

[E09] 去除所有空白字符
来源：http://dali.feifeiyinyue.top/Article/details/gtzocxbqrw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gtwmykocol.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyrjqgsm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtlxmhjobs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtzzicyhyw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gttqsplzln.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gtsafhnzrx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jianghu66.top/Article/details/gtlhyjjeip.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtltqogubd.html


<!-- 参考信息 -->