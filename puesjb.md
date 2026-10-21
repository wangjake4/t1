代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyemucfc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gtitvalfdz.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gtpbkbehas.html

Go:   // 无解构
来源：http://dali.fzhhl.top/Article/details/gtucidfcwh.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gtkjhckrql.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gtnubnybbq.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gthgqfygpm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fengsongda.top/Article/details/gtfagpacjc.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gtjciqtvdp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxqwvhhn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gthyfipnzq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gtynezcjak.html

Go:   // 无重载：用不同函数名
来源：http://dali.iojbl.cn/Article/details/gtosksewpc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gthbglwkvp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hysaishi.cn/Article/details/gthnyljlgg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrsvpxjhu.html

D. 数组 / 列表 / 集合
来源：http://dali.haohaochexian.top/Article/details/gttcnnbixx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtplpkobuy.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gtjrijeoir.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ivvv.top/Article/details/gtvkdqjqdg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.havefunace.top/Article/details/gtqqpplihc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gtcgghegyr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gtbtvdnuhv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.feifeiyinyue.top/Article/details/gtcrxzmmbb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gtiekagfyb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gogol.net.cn/Article/details/gtrdydduka.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenzaomai.com/Article/details/gtuqpqzufo.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gtkijwdhfa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yongpay.top/Article/details/gtuynqfgjp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gtvjnvjiga.html

JS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gtpepwnbnr.html

TS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtjdnawxqz.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlbszjcm.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtthfmzjci.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyevllae.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtnmziwphn.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gtzahoowhp.html

Py:   arr.insert(0, 0)
来源：http://dali.sysykeji.top/Article/details/gtqcbtwruk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xinyue.icu/Article/details/gtsfpnidoz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gtrhbxclnp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtzbbtvjlp.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gttiqwibup.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjymzhobk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gtlrzdelir.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtxluyqlpp.html

[D04] 删除元素
来源：http://dali.xuanzx.com/Article/details/gtmbmhpuap.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tanke756.top/Article/details/gtpxwltkcc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.svipenyu.cn/Article/details/gtxpzaayfp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gtntsgsldo.html

TS:   arr.splice(0, 1);
来源：http://dali.jyoumei.cn/Article/details/gtfloggone.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zycfv.cn/Article/details/gtwhwkirbv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.bjfxy.top/Article/details/gtmtlsmvlu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gtrgqaktux.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gtuugtbzov.html

[D05] 访问与修改元素
来源：http://dali.haohaochexian.top/Article/details/gthdxsvbno.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtskvlpxyr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqudhejo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtbtqfttrh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gtpgjnnznx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gtlthrkwlr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtlccvanxe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gthwwfnshp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtxnouwlfv.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtaknxlxsb.html

Py:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtbhkuorwf.html

PHP:  count($arr);
来源：http://dali.daxiang520.top/Article/details/gtnaunipwm.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtnjwzaucw.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtklrrbhck.html

Java: list.size();
来源：http://dali.zhoulong.xyz/Article/details/gtpcwhebiv.html

Go:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtglgjxshr.html

Ruby: arr.length; arr.size
来源：http://dali.sweek.top/Article/details/gthhksuqvz.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gtprchrkxb.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gtetugrsff.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gteqnxkfns.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.birdmap.top/Article/details/gtvsdhrtwm.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtcwsbefkw.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtjkkqvfza.html

Java: list.subList(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtccchvrce.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcjvlvuz.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gtkzksfkkv.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gtdzcpekmo.html

[D08] 合并两个数组
来源：http://dali.havefunace.top/Article/details/gtsthzlgsw.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gtidudxeyt.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gtbubxdaei.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gtwobusdgq.html

TS:   [...a, ...b];
来源：http://dali.zhongyouzk.top/Article/details/gtmaeujdzq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dashuyun.cn/Article/details/gtttbsfvbe.html

Go:   append(a, b...)
来源：http://dali.nanxinkj.top/Article/details/gthdjzqqqp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtadhopxjo.html

C#:   a.Concat(b).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtielsbmfl.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtkindjkfj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtjhenkrje.html

PHP:  sort($arr);
来源：http://dali.daria6918.cn/Article/details/gtesxhuufx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.redwolf501.top/Article/details/gtzspybxbm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gtzwosxbzq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gogol.net.cn/Article/details/gtdtebmyqf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtnyusjrvd.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtebwtsccp.html

C#:   list.Sort();
来源：http://dali.jyoumei.cn/Article/details/gtlutdxram.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gtjstgkpfy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gtmqijkkvs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gtiqaiskaj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gtrykvqndv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gthpqkdmed.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gtvnsducto.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gtwgdzwsap.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jyoumei.cn/Article/details/gtafpwnxwe.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gttassycql.html

[D11] 反转数组
来源：http://dali.yuanzhike.top/Article/details/gtolbjjpyf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gttgewtjec.html

PHP:  array_reverse($arr);
来源：http://dali.ybcxt.top/Article/details/gtouewxreo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gtznzgblue.html

TS:   [...arr].reverse();
来源：http://dali.jinqigfzy.top/Article/details/gtlylvgilm.html

Java: Collections.reverse(list);
来源：http://dali.jqgfzy.top/Article/details/gtvnorrtic.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gtrojcwcxu.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gtifdowbom.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkiwuhof.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gthieuaahf.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuzmcdbt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gtwxyqtulh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtzrnpirxd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gtpkkyjhds.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dashuyun.cn/Article/details/gthfvclcul.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtevjddvxm.html

Ruby: arr.index(x)
来源：http://dali.hnqzz.top/Article/details/gtyhpywnjo.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gtadhvozsz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenlongwang.top/Article/details/gtiikagibx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfvddvem.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gtkarqqgty.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtsymoafnr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gtmxxpvhhb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gtaarxjacp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gtjkbvivhp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlldgoxk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtxruaazoi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gogol.net.cn/Article/details/gtocrtpdso.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hammf.cn/Article/details/gtlvnjvzul.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtavsvsywt.html

JS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtbpybhfih.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gtwnfyzlnz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nwbrower.top/Article/details/gtychctdhp.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gtrffytmfx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtmefhxdti.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnqzz.top/Article/details/gtphbngbyi.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gtyqwchgbe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtxsczyqie.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtkgariquf.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtrjhfbniv.html

TS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtiqexdplq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgufenzy.top/Article/details/gtkgahlarx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gtbzjktymb.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gtwoowblpy.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtpbpteiwj.html

[D16] 求和与平均值
来源：http://dali.ybcxt.top/Article/details/gtjvjxzzoz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gtnfupincf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtbdaclwlv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtuoifsalj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtvjdfmkyi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gtarrdlspr.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gtjhcvsono.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ybcxt.top/Article/details/gtwxlxmxyj.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gtjespjvjo.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gtkqlizlzk.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtslugajrd.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gtpafdvtse.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gtnvpdhghq.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gtvetnvnbs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gtiutoussu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gtabuavcbz.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmjxpjav.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gttsxldids.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gtykcathja.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gtojwmjxqg.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gtfwpgkxqy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gtxkdwtfpv.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghyozyfy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuoaaxcic.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gtmrxdybso.html

Ruby: nested.flatten
来源：http://dali.xylfe.cn/Article/details/gtcnhxinet.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuanzx.com/Article/details/gtgxpsksdk.html

[D19] 按字段分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjzhpqbb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj202588.top/Article/details/gtvkbqnigd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gtkojagsvz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gtyijpedbi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtatqcfwiw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gtxnfrzdir.html

Go:   // 手写 map[string][]T
来源：http://dali.yongpay.top/Article/details/gtrsmetvob.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhengqikj.top/Article/details/gtrqnjkbld.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gtjowwrxmi.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gttwfqsfup.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyzzetmy.html

PHP:  array_count_values($arr);
来源：http://dali.yuxming.cn/Article/details/gtulyebnyz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtfikynxqp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtambidfnk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gtoulzavls.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gtrblpeplx.html

Ruby: arr.tally
来源：http://dali.hfpthk.cn/Article/details/gtxpygvvxk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gogol.net.cn/Article/details/gtmncmfzwz.html

[D21] 判断是否包含某元素
来源：http://dali.zycfv.cn/Article/details/gttvlrmeko.html

Py:   x in arr
来源：http://dali.redwolf501.top/Article/details/gtfttpkxpv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gtqkibnbgo.html

JS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtlpdekbbc.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtujgmwrnu.html

Java: list.contains(x)
来源：http://dali.nwbrower.top/Article/details/gtgpyzhlzs.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtdxdwgike.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gtbfjhsymm.html

C#:   list.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtxydzozwb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gtvjuhmyme.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sufxvd.cn/Article/details/gticlupvhg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gthtcsnoeh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gtrvocwutv.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gtzbbihhgz.html

Java: new ArrayList<>(list);
来源：http://dali.wangdashe.top/Article/details/gtfetkcwrk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtmeqgowjg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gtlaeqnaka.html

C#:   new List<int>(list);
来源：http://dali.316326.xyz/Article/details/gtlqakyvgo.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbbriavo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gtlvjenbsv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gtlpsiljgf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtwrcwrfxi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtfqabpufx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuanzhike.top/Article/details/gttfemmpat.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtsiditatb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gtqwzuihhi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gtvzahquly.html

[D24] 字典 / Map 基本操作
来源：http://dali.hywenlv.cn/Article/details/gtovlziizz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.mhx1999.top/Article/details/gtvkhstrzo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aizwys.cn/Article/details/gtzovwcihs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gtgykjglpu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gttszqnhbd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gttezlpeto.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gtazddtwqp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gtffwqcrzd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shzxlz.cn/Article/details/gtczweevuc.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gtdvnuprgn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hfpthk.cn/Article/details/gtgsqsspnw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daria6918.cn/Article/details/gtpodvfble.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtbdbqfkxs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.andypj.xyz/Article/details/gtoyjbvfqm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtzizrhwsy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gtougadyqo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgfzy.top/Article/details/gtykzkqlmi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtrggccfrp.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gtiubbqkjz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gtjkuqkmnt.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gthbeolzpm.html

JS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkotettur.html

TS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtbhxiuirl.html

Java: String.join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtquuxxczc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.snrcjt.cn/Article/details/gtgxekmmno.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtdrdtpggp.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtlwmhmrva.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtuefelsub.html

E. 字符串处理
来源：http://dali.svipenyu.cn/Article/details/gtfwivlyvs.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnlvmdwih.html

[E01] 拼接字符串
来源：http://dali.yonumen.top/Article/details/gtubefqgcg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gtvuuwwbyd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtworqiqil.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gtzjdshnuh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtppdbjoki.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gogol.net.cn/Article/details/gtgvpdzrlk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbcsbsvv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gtfelvytub.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtohbcrpuy.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gtliciykvu.html

Py:   "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gtlgzxucth.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gtlpbpltyz.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtverhtrni.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtlqzoagbv.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtmyrjnwmn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoxjyhth.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvrnsnty.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gtulqiobtf.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gtambbobjk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigufen.top/Article/details/gtsmqazhuw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtpoyjxhmo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtmjsbrtns.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gtaiaktibh.html

Java: s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gthoezzcmc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gtjwjracuy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gtnkxmrung.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gtncvjuguu.html

[E04] 查找子串位置
来源：http://dali.316326.xyz/Article/details/gtzzfhktdx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqrznozx.html

PHP:  strpos($s, "x");
来源：http://dali.jianghu66.top/Article/details/gtkgxwonnc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hongshengwenyu.top/Article/details/gthqqzeplv.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gthhccowcb.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gtouejgpgz.html

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gtktrwyrzl.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtmeglupew.html

C#:   s.IndexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtbbjbfqpp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tanke756.top/Article/details/gtidzwlfui.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cdnleiting.top/Article/details/gtfgkwldxc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jiagoushi.top/Article/details/gtjiyplzrq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfprlkbj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gtsdhcoyen.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtnoilpwzm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ydzc1.top/Article/details/gtqjcfxxie.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gtmgvopdyx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtheunhwlt.html


<!-- 参考信息 -->