代发 wailian999

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jyoumei.cn/Article/details/gthqodhtdw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gtzjxreqze.html

[D05] 访问与修改元素
来源：http://dali.sweek.top/Article/details/gtgxpqpfdg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtdxceguyl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtancnmtvx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtjsluxqiu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gtfuqytuij.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gttrdkwhgd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtuoxjihbx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtvdrnjoak.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gttipfvxij.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gtxxnkrhty.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtbsynyyga.html

PHP:  count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtlhkmivrv.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtkvdyjzic.html

TS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gtssswtayx.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gtfpfjwgtt.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtfvcvlxur.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gtjgegnpuz.html

C#:   list.Count;
来源：http://dali.hongshengwenyu.top/Article/details/gtajgrgyku.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gtylwycmkr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.vqdsnc.cn/Article/details/gtoknxxgnd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cashguo.top/Article/details/gtbvxfcgqk.html

JS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpulcshtw.html

TS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtitfehsuh.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtuomqkeyl.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gthcblidgd.html

Ruby: arr[1, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtyeopkniw.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtrsfwzzkb.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gtfsqoewnd.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gtwukurmez.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gthwgtsumq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gaohongyu789.top/Article/details/gtfzxwxdtt.html

TS:   [...a, ...b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbolsnhef.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gthynqryfj.html

Go:   append(a, b...)
来源：http://dali.wangdashe.top/Article/details/gthyvsdcsu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gtfacpggss.html

C#:   a.Concat(b).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtlpcjepet.html

[D09] 排序（升序）
来源：http://dali.xinyue.icu/Article/details/gtlgpzcfux.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtpnfetxng.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gtwznrytlu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhongyouzk.top/Article/details/gtehhzhaey.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtowakdvnh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.birdmap.top/Article/details/gtwjaiiefn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtedtfpezx.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtdzgjuihw.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gtwtrmbfys.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gttcamtagq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgfzy.top/Article/details/gtrvxgvrux.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gtujvrbmoj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtfukkoeql.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtwruyhukd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ybcxt.top/Article/details/gtoxxmpwvc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gtlaerdctk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hongshengwenyu.top/Article/details/gtddkuzljy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gtqxmpdldd.html

[D11] 反转数组
来源：http://dali.shangyingyoupin.top/Article/details/gtmiubrvip.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hysaishi.cn/Article/details/gtxwpakeht.html

PHP:  array_reverse($arr);
来源：http://dali.9152youxi.cn/Article/details/gtsndxaebo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gthoaogqmn.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gtdcazwtbh.html

Java: Collections.reverse(list);
来源：http://dali.316326.xyz/Article/details/gtvazokyxb.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gtfzaffflv.html

Ruby: arr.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtmtpljrbw.html

C#:   list.Reverse();
来源：http://dali.bjfxy.top/Article/details/gtdoskegab.html

[D12] 查找元素下标
来源：http://dali.yuanzhike.top/Article/details/gtioyiqjam.html

Py:   arr.index(x);  x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtlvyrapwj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtayxtpyqq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtouzhinhe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtefsiapkq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ppjwa.cn/Article/details/gtgkiteedz.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtkxuftsnt.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gtxtmjibdi.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gtbdoedlaj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gtzolcsgmi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gtsckccpyh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtegumwtia.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtbbznxjgk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gtdoebkiko.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.iojbl.cn/Article/details/gtmsntwhea.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gtwgokcxrh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtvfattjht.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtancnstcf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gtsmnvrvwl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gtksoyuzkg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gtmgkactqr.html

JS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtzakypdpm.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtguxuwalh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.smart0.xyz/Article/details/gtbqaxwask.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gtaievrnam.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtpmlenydb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfxtsqqb.html

[D15] 去重
来源：http://dali.jianghu66.top/Article/details/gtwxqfvqmi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gtbrkvdutq.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gtuvjdxfjb.html

JS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtirhiakzm.html

TS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gteaazrgto.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xylfe.cn/Article/details/gtelhsaxyh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangdashe.top/Article/details/gtoezwbnio.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gtprgrwqmm.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gtqcbyvksn.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gtapyefnqr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gthydcpyzz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtpjbiqsrp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtrnbphaig.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtdjwomehv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gtzofuoigv.html

Go:   // 手写循环累加
来源：http://dali.hnxiangtu.top/Article/details/gtyxjnflcw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtwpytedjt.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxubbnzz.html

[D17] 最大值与最小值
来源：http://dali.birdmap.top/Article/details/gtiswlnsmp.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtcyptixro.html

PHP:  max($arr);  min($arr);
来源：http://dali.tianlin.xyz/Article/details/gtiugrbyjj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gtijkrzgvr.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gtbkcbncpc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobtywvbx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtzzuiphsf.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gtesgssfup.html

C#:   list.Max();  list.Min()
来源：http://dali.zhongyouzk.top/Article/details/gtqifgqflr.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gtiebrhtpq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gticasfsdt.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchoyfctv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjepxwcyr.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gtjgyenubc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gtnbchheug.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtratsqcty.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrtauwye.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtllpjyqjd.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gtxgsglmtc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gtkzbtwyvg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dianchejie.cn/Article/details/gtubbeifkx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sysykeji.top/Article/details/gtamkllwsq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gthvfytyfu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gtuvuecndn.html

Go:   // 手写 map[string][]T
来源：http://dali.iojbl.cn/Article/details/gtjrwnhjct.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.birdmap.top/Article/details/gtkfofhkzv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtedztsjdf.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gtuhjwiuab.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gtlsvegbgt.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gtqzpyogts.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtkvexkwcq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtxukndazm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gtfivmqird.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gtodczbmjt.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gtldmjmqnc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gtedhabrpd.html

[D21] 判断是否包含某元素
来源：http://dali.xuanzx.com/Article/details/gtnaidmuuu.html

Py:   x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtdkjfroju.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gtgqmndaoy.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtaigacgmy.html

TS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtbzwippyl.html

Java: list.contains(x)
来源：http://dali.wangdashe.top/Article/details/gtuuzvkrbi.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahsqkeog.html

Ruby: arr.include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtqbfjjrsw.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtckjubkxp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cdnleiting.top/Article/details/gtzunkdajr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gtotacptyi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gtxnxkvcrj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gtsktyqblx.html

TS:   [...arr];
来源：http://dali.wangshuangyany.cn/Article/details/gtdvplrjor.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gtblptgyly.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yanxiufei.cn/Article/details/gtvvonsuhs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jiagoushi.top/Article/details/gttckckfaz.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gtuuuzxvoc.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gtbsucrvpd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.bjfxy.top/Article/details/gtbwbnicsl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gtfnawmplj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtfwfoecso.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtbehitdwy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.redwolf501.top/Article/details/gtjyhtmmil.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtrgifsqml.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258.top/Article/details/gtqtahmohe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxinkj.top/Article/details/gtkxiregbz.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gtjrtgjduy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtedxdunad.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gtjlkuekeh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gtkyszzqoi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gthtummxjc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhoulong.xyz/Article/details/gtfntkxsgv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtdlrtsnlr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gttzzthish.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gttmgjoxxh.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gtnoyuzffo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopumbsig.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gtzqhghguv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gtgveaztvi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.316326.xyz/Article/details/gtszpahwbz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtwpiyynxn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.andypj.xyz/Article/details/gthjjuzfky.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gtyuisthgr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtbiydbdiq.html

[D26] 数组转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtbgwxztqo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbiqpbybh.html

PHP:  implode(", ", $arr);
来源：http://dali.hnqzz.top/Article/details/gtrplsqqqo.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtprjwtkho.html

TS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtzxujixvl.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gthmbmzzad.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gtjjjzbtjd.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtkscrcfzk.html

C#:   string.Join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gtejcyukab.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthqwhpkep.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gtrvwftjnh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtjlgungnb.html

[E01] 拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gttrxbnnza.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gtaxivijwi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gtfrhelfey.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtxyuuznhp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtwggtslax.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sxryk.cn/Article/details/gtgueflhrw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtltfbjcrd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gtjpxcgoqa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtwcxobdeu.html

[E02] 重复字符串
来源：http://dali.jiagoushi.top/Article/details/gtjgxalmjo.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtjivtgoul.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gtvpoymwso.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtnodpaysp.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtpqiquzzq.html

Java: "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gttkzduiil.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnxiangtu.top/Article/details/gtezeikeke.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtasnserbc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tian-w.cn/Article/details/gtzelzezrb.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtklofnjbg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnxiangtu.top/Article/details/gtanqqajsn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthytbvwtx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtbdzscuan.html

TS:   s.slice(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtuwihtoxg.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtjovbrykv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gtisajautv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cqqwz.cn/Article/details/gtaaamcgil.html

C#:   s.Substring(1, 3)
来源：http://dali.dashuyun.cn/Article/details/gtkvyuydgs.html

[E04] 查找子串位置
来源：http://dali.tian-w.cn/Article/details/gthgogdnfk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gtznmnjdko.html

PHP:  strpos($s, "x");
来源：http://dali.ehwqpu.com/Article/details/gtrnltyvsv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gtrclwddbl.html

TS:   s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gthuwxvvxc.html

Java: s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtvrixupuv.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gtspitlpqp.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gteamibish.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvashnrg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gttddpigvg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtnfditdxn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhiwuduotai.top/Article/details/gtkbrmwxbc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtnujusrum.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gthmhvjmbr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtasjdlffv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yanxiufei.cn/Article/details/gtafevzvku.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gtlgplytde.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtdbytdkku.html

[E06] 替换子串
来源：http://dali.nwbrower.top/Article/details/gtjyhapetk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtupmcliur.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gttkxekjoe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtfjhkfvot.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtzmimjcgs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtovqgxgtb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtzqfqmtlc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtcoazyqzk.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gtppwupeng.html

[E07] 按分隔符拆分
来源：http://dali.jqgufenzy.top/Article/details/gttjqocgzg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yvedp.cn/Article/details/gtdttxwnju.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtrztaaoef.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dianchejie.cn/Article/details/gtfktmkhjy.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsuoekng.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jianghu66.top/Article/details/gtgpzzuzec.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zycfv.cn/Article/details/gtctamigas.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gtukrxoaoy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.snrcjt.cn/Article/details/gtkivjrddp.html

[E08] 数组按分隔符合并
来源：http://dali.dianchejie.cn/Article/details/gtavpzcpsr.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gtlwcszfjt.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gthxfmqhib.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtvridpmci.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtuvzasepx.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtrldnmald.html

Go:   strings.Join(items, ",")
来源：http://dali.hnxiangtu.top/Article/details/gtqzlzcokp.html

Ruby: items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtmpthobmn.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gtmwojuyeh.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gtxtpquueh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gtmypxqqsv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gtcqiupsib.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtftfzypmm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtwtwkjwzp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gttxxpwymz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jianghu66.top/Article/details/gtgkykrjzc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ybcxt.top/Article/details/gtddwurqto.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gtwdxnzftt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gtltvgrifs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtmsjxtasb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gtaqrhxlcp.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtynvqdyuv.html

TS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtwhzfiloe.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyziuxsd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtcjmlvoac.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtdxjfanha.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dashuyun.cn/Article/details/gttgsalklu.html

[E11] 反转字符串
来源：http://dali.shzxlz.cn/Article/details/gtszmyipfw.html

Py:   s[::-1]
来源：http://dali.zycfv.cn/Article/details/gtggnkdsdg.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtvzdlxewi.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtvrurmalg.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtdrmmytbx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtmitxnrvo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gtqlbxwdzy.html


<!-- 参考信息 -->