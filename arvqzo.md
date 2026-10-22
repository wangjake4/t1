代发 wailian999

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2wszpqrpb.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2qkfymfbp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aibaodan.cn/Article/details/gt2jpsefjqw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2kwqktsex.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aibaodan.cn/Article/details/gt2jhhktpij.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gt2rixlxrwi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuanzx.com/Article/details/gt2yjjeymzr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gt2zthpuops.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yvedp.cn/Article/details/gt2mirfbuuf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gt2kugaewgr.html

[D05] 访问与修改元素
来源：http://dali.aizwys.cn/Article/details/gt2rjsfwejt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2jzicbnkb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2kzvzgcko.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gt2nabtqjab.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gt2kzwwccwj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gt2bnkskfmv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2gycrugkp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2nnqthsvu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2aolgonnj.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gt2mahdqwnu.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2ovqclupk.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2heohysis.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gt2rbkjfxqa.html

TS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gt2xoizwgoi.html

Java: list.size();
来源：http://dali.sufxvd.cn/Article/details/gt2uauekkah.html

Go:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2ndggdher.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gt2zkttohdp.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gt2klbzupab.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gt2rtbwcvfp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gt2ntrfdbtt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmwczddi.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2cmplufta.html

TS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2fecsaiyv.html

Java: list.subList(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2omlwtael.html

Go:   arr[1:4]
来源：http://dali.guowangkeji.top/Article/details/gt2cwlyedrm.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gt2uuayqnuo.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gt2xwrkhmcv.html

[D08] 合并两个数组
来源：http://dali.cqqwz.cn/Article/details/gt2yjuvpcac.html

Py:   a + b;  a.extend(b)
来源：http://dali.pycfn.com/Article/details/gt2apzglxdj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhoulong.xyz/Article/details/gt2pocxsawj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guowangkeji.top/Article/details/gt2kvenjxyn.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gt2uzwesdqk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmtkcmlu.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gt2pqgmrsgx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lojpdwhf.html

C#:   a.Concat(b).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2hrdcvlff.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gt2ugmdmcig.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gt2gbbtirup.html

PHP:  sort($arr);
来源：http://dali.cashguo.top/Article/details/gt2vrjcqqzv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ryyfdvfn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gt2grovlgaf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gt2kxzknxui.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gt2ogveouwr.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gt2xhtifelb.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gt2vizjcpxr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gt2ygnykcxr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2yvgrwmmh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gt2xtzqtcwg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gt2uwfbjtpv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gt2dcursrjq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuanzx.com/Article/details/gt2tlcxbhex.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tianlin.xyz/Article/details/gt2wgmcabyr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenzaomai.com/Article/details/gt2zszqtzzz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yvedp.cn/Article/details/gt2uxsjymwp.html

[D11] 反转数组
来源：http://dali.sweek.top/Article/details/gt2csczfijo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guannengcc.top/Article/details/gt2ldcfxvel.html

PHP:  array_reverse($arr);
来源：http://dali.xylfe.cn/Article/details/gt2lqjkwdkz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gt2xzvtxgqp.html

TS:   [...arr].reverse();
来源：http://dali.fzhhl.top/Article/details/gt2yqhrweme.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gt2plhwflmt.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2vhrztdlq.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2qgclmuhh.html

C#:   list.Reverse();
来源：http://dali.yj202588.top/Article/details/gt2vlvtpsva.html

[D12] 查找元素下标
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhtfnmzb.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gt2aeyjpmfd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvolctwp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gt2fdbpujdf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2ydzffbwr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gt2xixzhyvg.html

Go:   slices.Index(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iagwhohs.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gt2vecdyphh.html

C#:   list.IndexOf(x);
来源：http://dali.chenlongwang.top/Article/details/gt2tjauegbw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gt2ofmmkiim.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gt2zeyygrcr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gt2ujnhjayt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gt2dtgyqyqw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gt2yrlnakfb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2eemorxyg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gt2fcnglyib.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ivvv.top/Article/details/gt2fcadfcyn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2fufztjat.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ybcxt.top/Article/details/gt2vpykoixt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.haohaochexian.top/Article/details/gt2xgmfsoex.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gt2mliwivwr.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2wbgbdsvs.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qtlbhizu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gt2lsksqjth.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2pmzpqqmu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gt2flkxldxj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2oahtdlbp.html

[D15] 去重
来源：http://dali.shuidangran.top/Article/details/gt2vhlaffww.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2hfxdzscn.html

PHP:  array_unique($arr);
来源：http://dali.yuxming.cn/Article/details/gt2teymypzg.html

JS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gt2prcbtjbb.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gt2mxnithre.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.9152youxi.cn/Article/details/gt2srtkidmu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cheryme.top/Article/details/gt2fsyfkcoc.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gt2qvqlvmor.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gt2nvqhhuxh.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gt2nvnzzzua.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2yglkiaxu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gt2nzaxkfpg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gt2eeujdzvo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2tofhzbxn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzlpjwyu.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gt2tmbwqdzg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sufxvd.cn/Article/details/gt2mjuijpkk.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gt2urzlqoij.html

[D17] 最大值与最小值
来源：http://dali.jqgfzy.top/Article/details/gt2pjajyjrv.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2ffdgdzro.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwsxgxcq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2ooqgbzpe.html

TS:   Math.max(...arr);
来源：http://dali.jqgfzy.top/Article/details/gt2mnjloobp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gt2qqmswrxi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gt2wcqaeaml.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gt2xkaymjck.html

C#:   list.Max();  list.Min()
来源：http://dali.shuidangran.top/Article/details/gt2vakpaxtf.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258888.top/Article/details/gt2cjlhiwuw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daria6918.cn/Article/details/gt2gttgfbdv.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obdibbdn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dianchejie.cn/Article/details/gt2oibzccwe.html

TS:   nested.flat();
来源：http://dali.nanxuanxn.top/Article/details/gt2keowybtl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gt2wyntsbyf.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gt2fhtnqzoc.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gt2jfkhgxwl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2ruwbybsx.html

[D19] 按字段分组
来源：http://dali.yueranfly.top/Article/details/gt2skyzjqeg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzesibxb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gt2gvjjjeel.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gt2ahnthnvv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gt2rtvcbpmv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gt2xahalgwd.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gt2yyqoienf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gt2mpelyeoz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlmgtpju.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gt2wgvrbbdc.html

Py:   Counter(arr)
来源：http://dali.sysykeji.top/Article/details/gt2qtwnopem.html

PHP:  array_count_values($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2svtvwwgd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikhfannn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ijbyxilm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwvwqflq.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258888.top/Article/details/gt2rfbdnxbj.html

Ruby: arr.tally
来源：http://dali.cdnleiting.top/Article/details/gt2ulwogsvq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gt2ylikkfsw.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gt2rpttvatp.html

Py:   x in arr
来源：http://dali.redwolf501.top/Article/details/gt2rtrniacs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxvgxfnw.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2hptknjhd.html

TS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2pmxclulo.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2loeyvpdn.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qahunqfp.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gt2vdwuqcjb.html

C#:   list.Contains(x)
来源：http://dali.havefunace.top/Article/details/gt2nvbehzpz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.quarkkingdee.top/Article/details/gt2sfzfzwir.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2rpbxtqkr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ppjwa.cn/Article/details/gt2syqjfesr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elgndbsc.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gt2otdyefbp.html

Java: new ArrayList<>(list);
来源：http://dali.yonumen.top/Article/details/gt2mvztynav.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogqcggxx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gt2mnciigbi.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gt2grejyvhz.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gt2vyyuetog.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gt2kgpxluwm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ydzc1.top/Article/details/gt2ilrgcweh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gt2qodlxkao.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gt2nbaeemdv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gt2fehiclmm.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2aohfewxb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jiagoushi.top/Article/details/gt2elhgwidu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2setoruzy.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmftwnnc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2beqkrytm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwqktzpg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gt2wamxmenk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gt2jeniegtm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gt2biogzefc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpkkzvi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gt2fyhnufnc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gt2garfwstg.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gt2uanzpsij.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gt2ovjiimqh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gt2dnzdjygu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gt2kdbvfxzz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gt2nojjmyaa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2qpmlvycv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigufen.top/Article/details/gt2mqrqbheq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2zhjnjhtu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zaulirga.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gt2dhmnfgwt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cucudq.cn/Article/details/gt2rfetnmum.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gt2shbbuftw.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2jztybqch.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2zckznwrq.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gt2rqwstcaz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ybcxt.top/Article/details/gt2toxdxdqi.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2uqbgbaft.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gt2xhfaeovm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2dvuzgcac.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gt2xjokcljb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2fywwyyez.html

[E01] 拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gt2hbuqrihm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gt2ppnlwluf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pycfn.com/Article/details/gt2gqjsqnyi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gt2ahbsfkmv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gt2mbimpwyf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigfzy.top/Article/details/gt2uwldthiu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gursvidz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gt2loruiynl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2ukvgctph.html

[E02] 重复字符串
来源：http://dali.yj202588.top/Article/details/gt2sqnjeqpo.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gt2bprqqoyt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cashguo.top/Article/details/gt2ugzwkjzp.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2kkzwukse.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2ekfjnjys.html

Java: "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zyarvoyj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2negqyixl.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gt2mqnmlcym.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.9152youxi.cn/Article/details/gt2lwmfnvkn.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2jaecykeh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tian-w.cn/Article/details/gt2psjxfiqh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpdhgfry.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2yjciarts.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gt2efbpmqov.html

Java: s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2egvegzty.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aibaodan.cn/Article/details/gt2hisqswig.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gt2midyllha.html

C#:   s.Substring(1, 3)
来源：http://dali.meibo888.top/Article/details/gt2lembtrpa.html

[E04] 查找子串位置
来源：http://dali.xylfe.cn/Article/details/gt2chlfqglt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gt2xvyepoen.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258.top/Article/details/gt2gevrcegd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cucudq.cn/Article/details/gt2mtxwacad.html

TS:   s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2uebvopla.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2jptmbcbg.html

Go:   strings.Index(s, "x")
来源：http://dali.hammf.cn/Article/details/gt2gejmhkej.html

Ruby: s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2wvfuifdb.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2hwvsuopf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xinyue.icu/Article/details/gt2styqoigx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gt2mgjxwyfi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pycfn.com/Article/details/gt2icwiywsb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2kebkxezy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gt2ccfkknmz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xeqevbfu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gt2puxwhupg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gt2sgkrgxds.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.birdmap.top/Article/details/gt2xzscmbgt.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gt2gazpshtj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2byyurqlc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gzhubu.top/Article/details/gt2rpafasdg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2qhrqijxv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2lvjkwybw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2bjxsrkla.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2ogdwchlb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2iwoahryg.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2ekwtbupd.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gt2cjmdxgsk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gt2jqytdlpf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qieunaio.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dashuyun.cn/Article/details/gt2quuavfgi.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gt2wocuhkdh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnqzz.top/Article/details/gt2jdgcguuf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cqqwz.cn/Article/details/gt2rpfvxmkt.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gt2pfcgtrbe.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gt2rujwbhmi.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gt2fvgqyipf.html

Py:   ",".join(items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zpfubcee.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwxxsqtz.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2vrvxsrbj.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2eghlciqo.html

Java: String.join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gt2obdmocvs.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkohnulu.html

Ruby: items.join(",")
来源：http://dali.nwbrower.top/Article/details/gt2mrjgbcdf.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtoucbjo.html

[E09] 去除所有空白字符
来源：http://dali.andypj.xyz/Article/details/gt2apjvtobv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tianlin.xyz/Article/details/gt2xulqqauv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2gqkyzmkw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gt2fubcdzml.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtdcsfpb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gt2imkbxarm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gt2hcytvyze.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gt2czddwofd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrmasnsm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gt2eiyambei.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2jtdoeelr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cheryme.top/Article/details/gt2hzunhqxx.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2tkcbiwyf.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2ykdmfejl.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2hqpjvmoo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2ablbdzii.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2wlmjwtdn.html


<!-- 参考信息 -->