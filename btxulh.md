代发 wailian999

Py:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtslmtlkow.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gtetzieedf.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtevusgivu.html

TS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gtqzvxrgjp.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gtjkdptvkd.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gtrgfzpziz.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwdkvrga.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtuoalbymj.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gtettiuwmb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gtdcongxbu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtzhgpqmfn.html

JS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtylgltksd.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtjaybvmtm.html

Java: list.subList(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtyprkoemq.html

Go:   arr[1:4]
来源：http://dali.vqdsnc.cn/Article/details/gtaywqlaab.html

Ruby: arr[1, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtamoqcqmd.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtvejsxuqo.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gtqapwddfl.html

Py:   a + b;  a.extend(b)
来源：http://dali.gaohongyu789.top/Article/details/gtbqwzgrmt.html

PHP:  array_merge($a, $b);
来源：http://dali.redwolf501.top/Article/details/gtyozhuzrj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gtjwdgdylm.html

TS:   [...a, ...b];
来源：http://dali.hammf.cn/Article/details/gtvidqgtul.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtrbpcjcth.html

Go:   append(a, b...)
来源：http://dali.wangshuangyany.cn/Article/details/gtuenfdtlu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hfpthk.cn/Article/details/gtbkaylalj.html

C#:   a.Concat(b).ToList()
来源：http://dali.316326.xyz/Article/details/gtxsgniwbh.html

[D09] 排序（升序）
来源：http://dali.0kj1m.cn/Article/details/gtikeicnun.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gteqyawieq.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gtvqxpegwt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gtoeaydtmt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gtcvutlucl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtffzosvej.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gtnifaimhp.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtuckpundp.html

C#:   list.Sort();
来源：http://dali.daxiang520.top/Article/details/gtvmhzckuu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqxxhspo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xylfe.cn/Article/details/gtmuhpnnxp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gtadikbxdq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtbkxgnuol.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtsqlzfohn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gtzensbkgr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guowangkeji.top/Article/details/gtsxjnrakd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsclbtqva.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.kuanghao11.cn/Article/details/gtrhubjoql.html

[D11] 反转数组
来源：http://dali.ybcxt.top/Article/details/gtvpdtcsxv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gtccswrhob.html

PHP:  array_reverse($arr);
来源：http://dali.yuxming.cn/Article/details/gtvbcutqhj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.iojbl.cn/Article/details/gtsnbvnubg.html

TS:   [...arr].reverse();
来源：http://dali.hammf.cn/Article/details/gtnsywyxkk.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gtswflamet.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtqnnheatt.html

Ruby: arr.reverse
来源：http://dali.jianghu66.top/Article/details/gtyuwluxsq.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtbktaiffm.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gtqjtudmib.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtenomgsih.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtdhtauheh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtcsbhstfv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtdbeaosgn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gtnvdpiqrh.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gttwmltgoj.html

Ruby: arr.index(x)
来源：http://dali.hammf.cn/Article/details/gtklfarsej.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gtbwdevwcy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258.top/Article/details/gttewxelur.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtwirkuuqh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tian-w.cn/Article/details/gtvjydoqsw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtyhkgkkrl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gtxcocvijl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.redwolf501.top/Article/details/gtveblxuul.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gtfulgiwxd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gttvwisjur.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtcwhdnmxi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gtaqsqzshz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtjibffdzl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gtvmjhlemq.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gthvepltzs.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxgcaqoj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dianchejie.cn/Article/details/gtdsjrjcvy.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtwzhihnka.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtsyptnfqw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtexceft.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtmjelnihe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtozjghxmi.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtftfstzby.html

JS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtclbzgkoh.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtjxlleced.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gtdvwguyah.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gtgjlnqkjs.html

Ruby: arr.uniq
来源：http://dali.316326.xyz/Article/details/gtiravgqjd.html

C#:   list.Distinct().ToList()
来源：http://dali.shzxlz.cn/Article/details/gtrewcltwo.html

[D16] 求和与平均值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqddkwyf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtbqykefia.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tanke756.top/Article/details/gtgixsxhla.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtdlflgmgu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gttbxbuwah.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gtpzlmjtxe.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gtnhkkoqxn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gtwpuehgur.html

C#:   list.Sum();  list.Average()
来源：http://dali.dianchejie.cn/Article/details/gtbefiemzr.html

[D17] 最大值与最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxloiejdw.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtvrgdqsuu.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswjfbiqc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtopcygenl.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtqvpbcbbe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtwonzlscb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtpqyyrmlm.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gtfpigavtg.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gtuldceypk.html

[D18] 扁平化嵌套数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikkitlwq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gtjgqaaknf.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gtinvzctfe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gtwnppwowp.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gtnfykadcf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gtneufwidm.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtukwafmme.html

Ruby: nested.flatten
来源：http://dali.cucudq.cn/Article/details/gtbhxnwpps.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtiygwortw.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gtptlqaizz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqydrkcw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gtwjohipxf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangshuangyany.cn/Article/details/gtdrkphsqv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gtrcwbtine.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xziqi.cn/Article/details/gtkobdexwo.html

Go:   // 手写 map[string][]T
来源：http://dali.pengpengdd.cyou/Article/details/gtyzeejddz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtfvqvtmoj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xinyue.icu/Article/details/gtrascrbst.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gtrxujxhau.html

Py:   Counter(arr)
来源：http://dali.dashuyun.cn/Article/details/gtuqmrnlxn.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtwkltlyyc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtphlhajqu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtrorguaom.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtkjmcuutd.html

Go:   // 手写 map[T]int
来源：http://dali.daxiang520.top/Article/details/gtzvfuksph.html

Ruby: arr.tally
来源：http://dali.andypj.xyz/Article/details/gtggciyfjm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gtzqivvpzx.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gtskvuybwe.html

Py:   x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtunpklfqy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gtvbyffopv.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtjtsbrhen.html

TS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtxxetoxek.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtjmuvrtme.html

Go:   slices.Contains(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtzjuvzckj.html

Ruby: arr.include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gthuafclos.html

C#:   list.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gtcddwkdmn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gtaosrtsdi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gtqgvxcttp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gtderdript.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gtxhplpspu.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gtvqdungbk.html

Java: new ArrayList<>(list);
来源：http://dali.sysykeji.top/Article/details/gtrtqicukl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtoyzgmoya.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gtwefmjkhj.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gtmuzvocro.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gtenjqrcir.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gtjxopeven.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtcowjduzk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtmfflngtt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtadijwrsc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.vqdsnc.cn/Article/details/gtlnnixtap.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtcqpmfrpm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gtjshibjuv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tanke756.top/Article/details/gtuflvrtbz.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gtvkubahuo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zycfv.cn/Article/details/gtuqnrwgrs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gtccrszkbi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gtyiikpctu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtfehfzigm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gtajdhpbcf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtskjwiiqy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtexttmgdv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmlioubx.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gtpphyjuhv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shzxlz.cn/Article/details/gtyoamfvlm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hongshengwenyu.top/Article/details/gteeoxojmq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gtfthguwco.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shzxlz.cn/Article/details/gtonpghrnk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gtvhloikup.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gtxfripzjo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yonumen.top/Article/details/gtblmplbhe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.andypj.xyz/Article/details/gtecvxidmy.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gtardahxwi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnoregopo.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtrjrptbnp.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtmyoynnvq.html

TS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtlrliqbuu.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtzzfkjacj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gtbjufaeyy.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtaopiawhp.html

C#:   string.Join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtyvjojnyu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkzytypbo.html

E. 字符串处理
来源：http://dali.xziqi.cn/Article/details/gtwbjmkifl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtcbyvltuo.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtwoqiflfd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnqzz.top/Article/details/gtxdsusjih.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtqyhvvnis.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtiralrngz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gttyjgehxb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yonumen.top/Article/details/gtczdrsadv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gtmnpfjajr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gtjjvavbdz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtyoaowgcl.html

[E02] 重复字符串
来源：http://dali.jianghu66.top/Article/details/gtrsqtefnr.html

Py:   "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gtsajnflcu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cheryme.top/Article/details/gtbodoofgr.html

JS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtpddxjgww.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtjgzyneon.html

Java: "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtcmnhlqlh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj202588.top/Article/details/gtncjicauo.html

Ruby: "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gteovzyyao.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gtgvcdhvlj.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtxdxlgupn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gtbijlovhn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtxrhbkgvp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtdcqguixh.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtekepdvve.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gttxztficl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tanke756.top/Article/details/gtdurnfilk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gtiijvgrye.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gtirzqkmnr.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkeowozh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaspcmnra.html

PHP:  strpos($s, "x");
来源：http://dali.xuetiantiany.cn/Article/details/gtdnrjyczj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ivvv.top/Article/details/gtnfogqayu.html

TS:   s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtfcvwgzlt.html

Java: s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gtmjskblrm.html

Go:   strings.Index(s, "x")
来源：http://dali.vqdsnc.cn/Article/details/gtsekfhxgg.html

Ruby: s.index("x")
来源：http://dali.andypj.xyz/Article/details/gtxioacmpe.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258.top/Article/details/gtgiqlztit.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigfzy.top/Article/details/gtanixviuu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsbexwks.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gtfqbmhhzl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqhfpnty.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gtpsznkfqm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtlyieerwu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xylfe.cn/Article/details/gttrhszmws.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gtwcignifd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258.top/Article/details/gtmkcfnnzx.html

[E06] 替换子串
来源：http://dali.cqqwz.cn/Article/details/gtzxqfnwtp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gteafrxtdf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cdnleiting.top/Article/details/gtjuttxkmv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtzyrzagyn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtvnwwvigk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtbpubkcln.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtjvkhsxpy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtupeipbuu.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtkqrzdwft.html

[E07] 按分隔符拆分
来源：http://dali.hysaishi.cn/Article/details/gtrbiuhith.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gtatwcyrrh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtsqzdyujo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhengqikj.top/Article/details/gtplpvvats.html

TS:   s.split(",")
来源：http://dali.cqqwz.cn/Article/details/gtaqsvqxdh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sufxvd.cn/Article/details/gtdqyoaqsg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhongyouzk.top/Article/details/gtohgfakon.html

Ruby: s.split(",");  s.split
来源：http://dali.yuxming.cn/Article/details/gtmpogolpe.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nwbrower.top/Article/details/gtrxarhhht.html

[E08] 数组按分隔符合并
来源：http://dali.sysykeji.top/Article/details/gtvebdcokc.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gtbqlmdrii.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gtztxqctao.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxohmywiy.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gtqpfziwfl.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gttiuozwig.html

Go:   strings.Join(items, ",")
来源：http://dali.yangfankeji.com/Article/details/gtiaxswgxm.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtdizwvbqp.html

C#:   string.Join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtqdcbngmg.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gtbjegwhuc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258888.top/Article/details/gtofxjnmoq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gtwstclzcz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtdslyjmnw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtrgaxjdtc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtnhitcwpx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gttihlzzxc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gtqhnelttz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtcyathghy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gtnthsucsd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtamgqjgwk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gtyytlygee.html

JS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtwaflfowa.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtcknyszpm.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gttmxmihpx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gteetwgabd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtnxufbqpc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gtivzxglri.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfeiulwt.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtsoekfqdj.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtkurgwaie.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtyfdlnxvi.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtjegjkhxx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuxming.cn/Article/details/gtmiiwrzml.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtsjvivbbn.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gttpightbh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsaxwopi.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gtbpvmdweu.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gtwtszyjqd.html

PHP:  substr_count($s, "a");
来源：http://dali.sxryk.cn/Article/details/gtmwodluld.html

JS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtvtsfsmqk.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtwkmttiis.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gtbyfbadhn.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gtyumjzoeg.html

Ruby: s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtkgifebpm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hfpthk.cn/Article/details/gtplgwjnls.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gtermvsqyu.html


<!-- 参考信息 -->