代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gtznjhbkod.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gtgjkvqwnf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuitiisko.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzxzculb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgufenzy.top/Article/details/gtvocevhys.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gtrxnfiooo.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gtmgaghaoj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtdxlctymi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtqhliqvuf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtyxhnbiwr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gtcntetddy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shzxlz.cn/Article/details/gtzyghbyew.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gthplwjjoa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gttfeyttse.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtkcgilfjc.html

[D06] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtjyumhwiz.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutaffrgx.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtpsqdvjfd.html

JS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtgeumqbsg.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gtzdegujct.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gtoqkqcwkt.html

Go:   len(arr)
来源：http://dali.yj20258.top/Article/details/gttzmusojt.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtqifarknk.html

C#:   list.Count;
来源：http://dali.haohaochexian.top/Article/details/gtgempwhuo.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gtlkwkqxnm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgfzy.top/Article/details/gtkdoptula.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gtufbxemoc.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtfklqwlim.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtxhnbicqn.html

Java: list.subList(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtyamnhmou.html

Go:   arr[1:4]
来源：http://dali.redwolf501.top/Article/details/gtwzmlmvlo.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvpraqfe.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gtgytfdmeu.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gtopstvokh.html

Py:   a + b;  a.extend(b)
来源：http://dali.c1oappe.top/Article/details/gtavklvivp.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gtkrbhfeds.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shangyingyoupin.top/Article/details/gtxexqcuei.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gtikuhnmhg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtkitcjlys.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gtklxyzium.html

Ruby: a + b;  a.concat(b)
来源：http://dali.vqdsnc.cn/Article/details/gtqrohtzky.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gtucnozjld.html

[D09] 排序（升序）
来源：http://dali.svipenyu.cn/Article/details/gtxinnuxwu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtnxjylrzb.html

PHP:  sort($arr);
来源：http://dali.gotoacloud.top/Article/details/gtxcxqffpt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.andypj.xyz/Article/details/gtcrxbmbgo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyljfdtty.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmklblmv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtfspovcqi.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtaydsuypc.html

C#:   list.Sort();
来源：http://dali.shuidangran.top/Article/details/gtnildcfye.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gtlozvizxw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gtdlmfiphy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gtnwladosq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtaycvtgmp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gttocdcxyu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.birdmap.top/Article/details/gtnnamceqz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gtsmqyocne.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tian-w.cn/Article/details/gtvfksuzvu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gtqdrgfbzm.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gtckgyuien.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.quarkkingdee.top/Article/details/gtlvkeykgu.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258888.top/Article/details/gtanurphrc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ehwqpu.com/Article/details/gtpqruwckw.html

TS:   [...arr].reverse();
来源：http://dali.yuxming.cn/Article/details/gtekuchwfm.html

Java: Collections.reverse(list);
来源：http://dali.quarkkingdee.top/Article/details/gthhzwjcea.html

Go:   slices.Reverse(arr)
来源：http://dali.mhx1999.top/Article/details/gtuhpmxtio.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gtbsutreih.html

C#:   list.Reverse();
来源：http://dali.meibo888.top/Article/details/gtgqwluuit.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gthpbrryds.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtwnaibkol.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gtlsmkdgdj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gttnujtymi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtfufiuxic.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tianlin.xyz/Article/details/gtjpvcxoxa.html

Go:   slices.Index(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtyrzexmju.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gtmojhlspe.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gtoltrbxkd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gtydnxuqzm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gtcevwqufn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtdybsnyhp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtcslmjpli.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtrrzjugjg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtsmwsfjhv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pengpengdd.cyou/Article/details/gtfbyrivxx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gthbdmbhui.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gtmzsxndvy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.haohaochexian.top/Article/details/gtjbbvmtur.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xylfe.cn/Article/details/gtbbrfnzxe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gtfaiyqtaf.html

JS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtkbahqmcp.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtopzjnnis.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtlxggccdd.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gthfpwhgfr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtlkesfafl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtufyrgarz.html

[D15] 去重
来源：http://dali.xziqi.cn/Article/details/gtvfwvylaa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtxpsjgbrq.html

PHP:  array_unique($arr);
来源：http://dali.fzhhl.top/Article/details/gthsupuztw.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtrbcafiln.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtlpqwpjtd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuanzhike.top/Article/details/gtuxhyiyhq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yangfankeji.com/Article/details/gtoiuggabd.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gtibupkhkf.html

C#:   list.Distinct().ToList()
来源：http://dali.zycfv.cn/Article/details/gtqdxqmmkb.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gtmbmqvlyu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gtozscrkcq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gtebcrfoqy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtinjupive.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtgvyzjqts.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gtknenfxia.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gtuqdbekwp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnqzz.top/Article/details/gtmyrajveu.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gtlclgpwnj.html

[D17] 最大值与最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtveazwnhv.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gtbhhqeicd.html

PHP:  max($arr);  min($arr);
来源：http://dali.yangfankeji.com/Article/details/gtcxnyajti.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtwtddvgco.html

TS:   Math.max(...arr);
来源：http://dali.chenzaomai.com/Article/details/gthfckzsvb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gtriiyizov.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtlhrapgpd.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gtkosloosa.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigfzy.top/Article/details/gtaturosav.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtaxjsimmg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gttojwoxwu.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvzqemdu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daxiang520.top/Article/details/gtdjxpnksb.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gtfkcojfht.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenlongwang.top/Article/details/gtajerkcty.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gtnblkaqsg.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gtdopztxgi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gttexqenna.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gtheqnnzaw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangdashe.top/Article/details/gtljdjplye.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.birdmap.top/Article/details/gtjdludalk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuanzx.com/Article/details/gtbdtdfmaa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gtycgmveyx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gtfcnjfvpp.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gtpccabwlq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gtkmaddtig.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gtjrgejdts.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtfyjywepl.html

Py:   Counter(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtolhaiziy.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtrhtxnlis.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtmcvjvhim.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpjbfzcl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gtbxjleagw.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gtpuptajby.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gtumftuuot.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hongshengwenyu.top/Article/details/gtywtpejer.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gtnohnovkv.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gttlrrlicx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gtczozxtyl.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtqbdvgxxc.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtjigxujzk.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtzfacnsey.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtfbhhajej.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtrvlnbfxy.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtcnympqat.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cheryme.top/Article/details/gtfessskbj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gtbtkzznrv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guowangkeji.top/Article/details/gtaacyccmk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shzxlz.cn/Article/details/gtxflakcmy.html

TS:   [...arr];
来源：http://dali.hnqzz.top/Article/details/gtljmlwzla.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gtqikicknp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gtzmxwwnny.html

Ruby: arr.dup;  arr.clone
来源：http://dali.mhx1999.top/Article/details/gtvqnhiwlr.html

C#:   new List<int>(list);
来源：http://dali.jianghu66.top/Article/details/gtqxrvpvpl.html

[D23] reduce 累积计算
来源：http://dali.yuxming.cn/Article/details/gtuiutgktt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gtfyxlvizo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gtwnfyhvaj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtoawzkudz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtshcyjsux.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gtmfhrxisc.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gtnhqmodxn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ehwqpu.com/Article/details/gtecqqhupj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgfzy.top/Article/details/gttjfpqitr.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gteoptzopf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gtvvcatkfv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jlsjyb.cn/Article/details/gtclkyefvk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gtdrjudcmk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtglxrtqcc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gotoacloud.top/Article/details/gtyherqczi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gtunlmohqf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtahriohfm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ydzc1.top/Article/details/gtzgegtmtj.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gtzkvuxstk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gtrvopdibs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxuanxn.top/Article/details/gtgcwbarly.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gtxgkblpuv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ydzc1.top/Article/details/gttzhgulir.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtxoqmlmsu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.bjfxy.top/Article/details/gtseqjohsv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gtukhfcdzn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sxryk.cn/Article/details/gtcnrdbjdd.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gtvkztsxza.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aibaodan.cn/Article/details/gtfeurljnn.html

PHP:  implode(", ", $arr);
来源：http://dali.ivvv.top/Article/details/gtpkcutcal.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtfduwynem.html

TS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtlbdujovk.html

Java: String.join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtmzevchla.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtncouqbzg.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtobcrsuim.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtdlgrszub.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkbrofzt.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gtyaakbemm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtadvzeazx.html

[E01] 拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtifurfbun.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aizwys.cn/Article/details/gtdphrvadv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.mhx1999.top/Article/details/gtrnjhihkq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtleqtxyhc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtcilrwavl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gtgesimfya.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcpuetsv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gtkawhdtfi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtajfvpwos.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gtretdiocw.html

Py:   "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtfcftxgxy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.mhx1999.top/Article/details/gtdoiuapfr.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtfrzifxyy.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtuowmohck.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyuwvshd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxttzbrl.html

Ruby: "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gtqeznifsm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gtvpaojsdy.html

[E03] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtyceqwjku.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gtqluoyaqi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gthlqllaxd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtzubozyjg.html

TS:   s.slice(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtlrszsdmd.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gteijitccx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gteakmzjfv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.snrcjt.cn/Article/details/gtckxrdpeg.html

C#:   s.Substring(1, 3)
来源：http://dali.tianlin.xyz/Article/details/gtgotmxkwd.html

[E04] 查找子串位置
来源：http://dali.chenzaomai.com/Article/details/gtpcltumpy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtdxpymscl.html

PHP:  strpos($s, "x");
来源：http://dali.daxiang520.top/Article/details/gtktqahuae.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shuidangran.top/Article/details/gtgzfuyqmd.html

TS:   s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtxzzixicc.html

Java: s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtnphqytct.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gtpucjhklh.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtaktrrruq.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gtmjgcsomx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.kuanghao11.cn/Article/details/gtyjmgmvrz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenlongwang.top/Article/details/gtgwcuevku.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hywenlv.cn/Article/details/gttqngqrsb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtepjdrucx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jyoumei.cn/Article/details/gthayvbxih.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtiqbueocl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gtdwegoial.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dianchejie.cn/Article/details/gtivaxjjvo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtxouvprgp.html

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gtczfrszwz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gtrrgyksdp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gtttwahijo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtrvzgtpex.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtbhdevqtc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtsvtebkaf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtjrhikmze.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtuokhrrfu.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gthymnhreh.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gtpxjdwjni.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbesgmvgj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gttbyqgsbz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangdashe.top/Article/details/gtsuycplsj.html

TS:   s.split(",")
来源：http://dali.c1oappe.top/Article/details/gtcnzlvisa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteezzsfbm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtmhkugxpd.html

Ruby: s.split(",");  s.split
来源：http://dali.sxryk.cn/Article/details/gtgvrwsxex.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nwbrower.top/Article/details/gtasnrlido.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gtsgkylufq.html

Py:   ",".join(items)
来源：http://dali.meibo888.top/Article/details/gtdrradaac.html

PHP:  implode(",", $items);
来源：http://dali.haohaochexian.top/Article/details/gthljzgzbo.html

JS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtomnwvefq.html

TS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtuirlvetv.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gtugcszwvb.html

Go:   strings.Join(items, ",")
来源：http://dali.sxryk.cn/Article/details/gtihogiyld.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtjgmqmmdt.html

C#:   string.Join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneahsfdu.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gtiwickyzo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gtesvlyoqw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gtojxruddd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtfbpuzgtv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtfbjgarmt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gtpikfvgme.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.meibo888.top/Article/details/gtoswvhode.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fengsongda.top/Article/details/gtjudtumzv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gthiyxdllx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tianlin.xyz/Article/details/gtrsvaqpnq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrscufci.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gtgyrfjjzz.html

JS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtcnkkconq.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtvrxyrizq.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtzzwjebvf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtqfazkaoq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtqnijuqgl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapufwsoe.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtejfjhijm.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtydtfjnsd.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtssutgwcb.html


<!-- 参考信息 -->