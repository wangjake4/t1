代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtzlqygtcy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xylfe.cn/Article/details/gtutffooxn.html

Java: // 无解构
来源：http://dali.yvedp.cn/Article/details/gtsqcdswec.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtffwtxlwu.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gtknfqdhid.html

C#:   var (a, b) = pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtednlsito.html

[C16] 函数 / 方法重载
来源：http://dali.havefunace.top/Article/details/gtgzvgtasl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.vqdsnc.cn/Article/details/gtmybaipsx.html

PHP:  // 无重载
来源：http://dali.daria6918.cn/Article/details/gtcrartpws.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gtseuaypwu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhoulong.xyz/Article/details/gtcbnoxmaq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gtlvjqjltn.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gthfwdtujp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gtxxzzbyer.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gtzxcqcvbk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzbufujgt.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gtjpavasgc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtbymrepbf.html

[D01] 创建数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gtroksovxv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gtwgrsvzer.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daxiang520.top/Article/details/gtxinpeahr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtsilxudtb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gtnfkuhtfa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpbszigi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sufxvd.cn/Article/details/gtuivbpxbw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqxfauwx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gtemiwyrjg.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gtbzdenlkd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hfpthk.cn/Article/details/gtmvmfsjlh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtoqemkydi.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtbnvpnofi.html

TS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtlbmhclxv.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtrpualxgn.html

Go:   arr = append(arr, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtylnutjuc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhongyouzk.top/Article/details/gtxnbgzurq.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gtfdldfdwp.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gtkxcesazr.html

Py:   arr.insert(0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtkqpyhrdl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gtpkwwiyld.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gtnxpbfhtq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gtculqwrpk.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtowmbqske.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gtaaahagca.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxuanxn.top/Article/details/gtdqablskl.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtzjatekoh.html

[D04] 删除元素
来源：http://dali.ehwqpu.com/Article/details/gtndzpbhff.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhengqikj.top/Article/details/gtgmqxgumy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258888.top/Article/details/gthxlfioxg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.svipenyu.cn/Article/details/gtihnpsbmk.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gtpczdxugx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gtrrhzweuk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.haohaochexian.top/Article/details/gtipegjlyt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ybcxt.top/Article/details/gttatgcixe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yueranfly.top/Article/details/gtrqbuswpf.html

[D05] 访问与修改元素
来源：http://dali.yj20258888.top/Article/details/gtxkjfpmuj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtklhcgenr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtbweliolm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtsodvzenh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ydzc1.top/Article/details/gtnzxkhdbm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gtsbkwbehj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtpckjdqhj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtmfktnxcp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtwynndjpi.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gtokjprlcs.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtscsmuiob.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtsrucmugp.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtmvajwbqd.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtstemixrd.html

Java: list.size();
来源：http://dali.ppjwa.cn/Article/details/gtbesuazza.html

Go:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtsszlejur.html

Ruby: arr.length; arr.size
来源：http://dali.gotoacloud.top/Article/details/gtoejtelti.html

C#:   list.Count;
来源：http://dali.guowangkeji.top/Article/details/gtieatuwvv.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gtzltnpdck.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gtlbdgxixw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yvedp.cn/Article/details/gthqrjpzzb.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtwwjfsqpt.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtcotlxolr.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtwwduegkc.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gtuknczppj.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gtsctpgsox.html

C#:   list.GetRange(1, 3);
来源：http://dali.shuidangran.top/Article/details/gtrbntxxqm.html

[D08] 合并两个数组
来源：http://dali.cashguo.top/Article/details/gthapgosem.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gtsehvtlcd.html

PHP:  array_merge($a, $b);
来源：http://dali.hfpthk.cn/Article/details/gthipxwrga.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.vqdsnc.cn/Article/details/gtynrcfjzj.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gtqwairqwv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gtqintqdqo.html

Go:   append(a, b...)
来源：http://dali.tanke756.top/Article/details/gtxubvhozk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gtmihutywc.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtcffreyrs.html

[D09] 排序（升序）
来源：http://dali.nanxuanxn.top/Article/details/gtkhxfsvsx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtfehewqul.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gtquxxixqn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcvxgrsv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnqzz.top/Article/details/gtyfclmuit.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gtzlpqyxom.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtcflpovco.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtimttccmg.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gtipnqvpmw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.birdmap.top/Article/details/gtlsvjwenk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuxming.cn/Article/details/gtrzmyfari.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gtcmaknpoh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtmxmknhrh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gteobyhrvl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guannengcc.top/Article/details/gtcvezrsgs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.haohaochexian.top/Article/details/gtlsyxzyqy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gtqmpnwtdk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.svipenyu.cn/Article/details/gtcmtwfcll.html

[D11] 反转数组
来源：http://dali.hongshengwenyu.top/Article/details/gtgufilfaw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxuanxn.top/Article/details/gtiisbonnj.html

PHP:  array_reverse($arr);
来源：http://dali.gzhubu.top/Article/details/gtzdlxywlz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gttmtpgqzk.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijboavby.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gtwfdoqygm.html

Go:   slices.Reverse(arr)
来源：http://dali.yongpay.top/Article/details/gtmaemdmxu.html

Ruby: arr.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtswgrulud.html

C#:   list.Reverse();
来源：http://dali.chenzaomai.com/Article/details/gtfmcuulqp.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gtorhyyvyl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtcmzyfvib.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shuidangran.top/Article/details/gtkzmmqkoo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvnaaxak.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtbezyyecq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gtdkvtxike.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gteknmupxx.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwpmzjsf.html

C#:   list.IndexOf(x);
来源：http://dali.cdnleiting.top/Article/details/gtszcssiol.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gtysgjaquv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daxiang520.top/Article/details/gtumcymxys.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gttcvmacqy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtksobuccn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtdvfhjlds.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gzhubu.top/Article/details/gtdtywhasr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gtubfnjepx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqrovnpp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gtjzxtgmbe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gtcbcpkoao.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aibaodan.cn/Article/details/gtztsftndl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gtcjoyydfg.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gthjvfymrr.html

TS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gtufadgmjv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.svipenyu.cn/Article/details/gtzifgxrrk.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtqjfrbzzz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtxciowmsq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtznecphdr.html

[D15] 去重
来源：http://dali.zhixingplan.top/Article/details/gtecskqhgv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtsppmsugu.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gtdratyker.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtqrlalcod.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtwccoqsmo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.316326.xyz/Article/details/gtzjbvtztr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gtzdnllwmp.html

Ruby: arr.uniq
来源：http://dali.cdnleiting.top/Article/details/gtmppkadgm.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gtkcqxpkpv.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gtnflhedyp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtifyuoxtl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gtmfwtblmr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gtqncvptds.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtlwovgdqm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gtfqjolufy.html

Go:   // 手写循环累加
来源：http://dali.yongpay.top/Article/details/gtewtufrae.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtuvgyzvok.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gtkowefyfu.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtpuscsmwu.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gtojnhrvgf.html

PHP:  max($arr);  min($arr);
来源：http://dali.xylfe.cn/Article/details/gtstlimldt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj202588.top/Article/details/gtdbjkuyrn.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtlbryraoc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnofqykye.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtnggxshmd.html

Ruby: arr.max;  arr.min
来源：http://dali.nwbrower.top/Article/details/gtkgjcwtwv.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gtfovqrwty.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gtlnyjzfgu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gteimcsmkn.html

PHP:  array_merge(...$nested);
来源：http://dali.yangfankeji.com/Article/details/gthqetplfr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtdjpokclj.html

TS:   nested.flat();
来源：http://dali.zhiwuduotai.top/Article/details/gtqvuwjmjw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gtraobpomw.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gtupivuskl.html

Ruby: nested.flatten
来源：http://dali.c1oappe.top/Article/details/gtamhqmvdf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtubpwfnjs.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gtfumerpvq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gzhubu.top/Article/details/gttlhetgfp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gtyzsngqvf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jiagoushi.top/Article/details/gtvcwriwbz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsukpierq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gthzhmzmzl.html

Go:   // 手写 map[string][]T
来源：http://dali.chenjidiqi.icu/Article/details/gtkjyscdzu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gtkilnbyub.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yvedp.cn/Article/details/gtiefsfpqc.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gtqxufyfin.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gteyyftxrx.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gtcqfirtoa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtxwakkcmi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtbfgmgcbr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xylfe.cn/Article/details/gttosidvep.html

Go:   // 手写 map[T]int
来源：http://dali.nanxuanxn.top/Article/details/gtvlomhprc.html

Ruby: arr.tally
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwrnzmup.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gtoltgqwcy.html

[D21] 判断是否包含某元素
来源：http://dali.9152youxi.cn/Article/details/gtrujkstwx.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gtngewaytl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.vqdsnc.cn/Article/details/gtfqqoltec.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtnrococzy.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexaplutv.html

Java: list.contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtrtlandjk.html

Go:   slices.Contains(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtnhqknezl.html

Ruby: arr.include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtadibzljj.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtedxjllba.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sufxvd.cn/Article/details/gtjavmeuuc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaroxzcnc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gtbgfgbrne.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xziqi.cn/Article/details/gtewzcbkgw.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gtjrsxkqze.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtelddcpti.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.vqdsnc.cn/Article/details/gtxxhbvzox.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shangyingyoupin.top/Article/details/gtdcsayghi.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gtyllsryis.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gtvmwmsmxy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gtbmwmcprl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gtdiuscshl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtedcjonny.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtazazkdez.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gtqxnfniwt.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtrkpivxhh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daria6918.cn/Article/details/gtqiuxcsie.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gtnjsrdjfa.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gtjyoxguyu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gtnqewtnfi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhoulong.xyz/Article/details/gtubbeoiyh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangdashe.top/Article/details/gtcvwaslla.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbefaubsk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenzaomai.com/Article/details/gtoebdqqog.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gthpyztyvj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gtlmwaseze.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnxobtcn.html

[D25] Set 集合去重与交并差
来源：http://dali.bjfxy.top/Article/details/gtezvtmopv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gtpuafxony.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.bjfxy.top/Article/details/gtzeigefbf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258888.top/Article/details/gtcqbbalzl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gogol.net.cn/Article/details/gthuwdljdp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gtlpwfcpfi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.svipenyu.cn/Article/details/gtlajdvope.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gtgmidsiff.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gtdpzauogk.html

[D26] 数组转字符串
来源：http://dali.sxryk.cn/Article/details/gtmghsiskn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.andypj.xyz/Article/details/gtuhsjcwph.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gtuqomvsyq.html

JS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhzellvk.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtfbxjkprq.html

Java: String.join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtcnfcukpu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gtoyxtlsli.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtiffkxyyc.html

C#:   string.Join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtkizshrbh.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcfxonvfn.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gtgjghxtzf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtyawymffj.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtuqleqxgz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yongpay.top/Article/details/gtuqexqjrh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhongyouzk.top/Article/details/gtbujxjcoi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gtamegdmlc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtbaavfpce.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guowangkeji.top/Article/details/gtyvsbmisb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gtnvfbyoxw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrcifevi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtqtbpvwla.html

[E02] 重复字符串
来源：http://dali.gotoacloud.top/Article/details/gtvllhbvfh.html

Py:   "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gterhzpket.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yanxiufei.cn/Article/details/gtrgzvnjww.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtapaptupr.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtylgijfuu.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gthbuejvxe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aibaodan.cn/Article/details/gtwbsnyrzh.html

Ruby: "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gtixnjpolj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gtcyfbzjdv.html

[E03] 截取子串
来源：http://dali.birdmap.top/Article/details/gtnsdtnssq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gtyvdxcasl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gttygyldyo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtliwhsovr.html

TS:   s.slice(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgyoodzo.html

Java: s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtpmvmcgtz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtuoodzopj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cdnleiting.top/Article/details/gtphyoqvoc.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gtgljpbnbv.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gtwhzvnunu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtejxjvsrl.html

PHP:  strpos($s, "x");
来源：http://dali.pycfn.com/Article/details/gtalkjaloz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gtmpegxyge.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuzrkzyt.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtfvzvnqge.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258888.top/Article/details/gtuchvatat.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtckxgkuxy.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtxocuhhyb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xinyue.icu/Article/details/gtauyofiwd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gtfpltqslx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtjrbwbzid.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gttonkanea.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gtuzgzhfcj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtjptwqhqd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gogol.net.cn/Article/details/gtlkymwanp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tian-w.cn/Article/details/gtwoiqpnwo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtveoqmvmh.html


<!-- 参考信息 -->