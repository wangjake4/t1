代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ehwqpu.com/Article/details/gtzjflopmi.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gthzhlbayi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gaohongyu789.top/Article/details/gtirqdeurd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.vqdsnc.cn/Article/details/gtrkostetk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtilfnupzk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258.top/Article/details/gttjamnmbl.html

Java: // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gtkpesceje.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gtjduogcki.html

Ruby: a, b = pair
来源：http://dali.yj202588.top/Article/details/gtevxdfcwk.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gtgywtbpsy.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gtmverderb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gtofnhzcln.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gtvppqorvc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jlsjyb.cn/Article/details/gtbayrpbyd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fzhhl.top/Article/details/gtjmnmvivc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxuanxn.top/Article/details/gtavumzgtb.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gtliqxjlln.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guannengcc.top/Article/details/gtsxdvnfel.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.andypj.xyz/Article/details/gtxfsxgffb.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkrucxope.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gtiglphsdj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtdgrhiega.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gtsmamzjpy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.9152youxi.cn/Article/details/gttbdpnafo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zycfv.cn/Article/details/gtgzmrqenr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cheryme.top/Article/details/gtxrqvvzhe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnxiangtu.top/Article/details/gtpzerupmf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtbpmbronm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cdnleiting.top/Article/details/gtzgdjrsvn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gtedxwuxlm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daxiang520.top/Article/details/gtrqbwnldr.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gtshmxgsrd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gtaituylig.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.svipenyu.cn/Article/details/gtsayexoxr.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjfzuoja.html

TS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gtqtbfkulf.html

Java: list.add(4);
来源：http://dali.gzhubu.top/Article/details/gtauvpedxg.html

Go:   arr = append(arr, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtvjqcgnpn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gtjcwykhas.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gtugzztoua.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtsrmeursq.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gtydikpmix.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtjtefeueo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sxryk.cn/Article/details/gtocosfdsp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtcgkaflmf.html

Java: list.add(0, 0);
来源：http://dali.yvedp.cn/Article/details/gttdmrzmuh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.c1oappe.top/Article/details/gtcrglgmwx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtmghpgjmp.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtmmnpasgd.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gtefitamva.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dianchejie.cn/Article/details/gtvquodhre.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangdashe.top/Article/details/gtnemmrcpv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aizwys.cn/Article/details/gtpetdlmha.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gtzfnmoofc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gtgkvrqmqg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.birdmap.top/Article/details/gtnueyuipi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gtfvsrnscu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gtpktpppwi.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gtfkouqebq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtbwwpjlly.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtjjhyczwj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtithnojrp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gtwdqpvrtw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbafoxgz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtumvdgykw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryjkjowg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtxtbpipew.html

[D06] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscwwvjat.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtagqqwwll.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdontyedx.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecpshiyo.html

TS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxicsbwvj.html

Java: list.size();
来源：http://dali.kuanghao11.cn/Article/details/gtifjgjxex.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtwjhkkltz.html

Ruby: arr.length; arr.size
来源：http://dali.cashguo.top/Article/details/gtmvemracq.html

C#:   list.Count;
来源：http://dali.nwbrower.top/Article/details/gtblvogtbr.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gtbxqjvyhb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gtdwoocqti.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yongpay.top/Article/details/gtykllmbmm.html

JS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtgyirfwxb.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtpupreczy.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtmeylxdhe.html

Go:   arr[1:4]
来源：http://dali.zhoulong.xyz/Article/details/gtemctadpu.html

Ruby: arr[1, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtyljfvcwu.html

C#:   list.GetRange(1, 3);
来源：http://dali.guowangkeji.top/Article/details/gtupwwysaw.html

[D08] 合并两个数组
来源：http://dali.jinqigfzy.top/Article/details/gthibglhto.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtasfoxmhc.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtbtalqbkw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pycfn.com/Article/details/gtpjocoawg.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gtfwgmlaot.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtectkcdsl.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gtdprkkxrk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daxiang520.top/Article/details/gtxrxjsqkm.html

C#:   a.Concat(b).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtjzmdsydq.html

[D09] 排序（升序）
来源：http://dali.sysykeji.top/Article/details/gtrofprrev.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtxmlmpjen.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gtephtfqib.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gtujesvqkm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gtaomujdnu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shangyingyoupin.top/Article/details/gtnclfpozb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtxzfrhkao.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevnppnpk.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gtktezkblb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gotoacloud.top/Article/details/gtwfrvxlkk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtgicvmpxw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gtbznaeucg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtubarazpx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gtbhegbgtk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yongpay.top/Article/details/gthirrtffz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cashguo.top/Article/details/gtqpfnmkdw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zycfv.cn/Article/details/gtvrijwqkp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gtcrjibwmi.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gtxlpmzica.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigufen.top/Article/details/gtqnpfrgbn.html

PHP:  array_reverse($arr);
来源：http://dali.yangfankeji.com/Article/details/gtltemzhsj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shzxlz.cn/Article/details/gtdmydsxcu.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gtymnxcjau.html

Java: Collections.reverse(list);
来源：http://dali.quarkkingdee.top/Article/details/gtswmikptq.html

Go:   slices.Reverse(arr)
来源：http://dali.havefunace.top/Article/details/gttxnwhfua.html

Ruby: arr.reverse
来源：http://dali.zhoulong.xyz/Article/details/gteipvtvze.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogwmzxit.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gtmifiphqn.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gtmftznmpq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtbntyyllo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttovroirn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gtjnzkptvf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gtodcuedku.html

Go:   slices.Index(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtvqjcecdz.html

Ruby: arr.index(x)
来源：http://dali.hammf.cn/Article/details/gttdrnqsdx.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtdgvuulas.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtihdjygok.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtrijgljst.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gtdiopebzu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtazxrayll.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gtowjioivv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xylfe.cn/Article/details/gtpskiiklr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gtiylaqlca.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cucudq.cn/Article/details/gtwqkgxpyj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtbujmcaez.html

[D14] 映射转换（每个元素变形）
来源：http://dali.svipenyu.cn/Article/details/gtqfhaefgd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtvgzlyfiy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gtczghvkcd.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtrpypgucv.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtwdtvwden.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gtmvawrvud.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtlohzkznk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtchjcehwd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtrfratkjr.html

[D15] 去重
来源：http://dali.tanke756.top/Article/details/gtyjjgzlxg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtabyoqgtt.html

PHP:  array_unique($arr);
来源：http://dali.svipenyu.cn/Article/details/gtquuhbwvy.html

JS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gteakhtvsy.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtzftdsdmg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gtsyzdlevv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.mhx1999.top/Article/details/gtovhgtmdx.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtmsggqlck.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gtkfvtycmv.html

[D16] 求和与平均值
来源：http://dali.meibo888.top/Article/details/gtktiwtmgu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtqnigzmbd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtcnannmzc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gttcheizqe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtjyagcril.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gtxokvxtny.html

Go:   // 手写循环累加
来源：http://dali.sysykeji.top/Article/details/gtyimbhtnl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuanzx.com/Article/details/gtrnlpjlhr.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258888.top/Article/details/gtnueaonue.html

[D17] 最大值与最小值
来源：http://dali.pycfn.com/Article/details/gtnpubhvjz.html

Py:   max(arr);  min(arr)
来源：http://dali.316326.xyz/Article/details/gtzvodemzx.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangdashe.top/Article/details/gtrppeatii.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gtbofompox.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gtwtkcifia.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jiagoushi.top/Article/details/gtjviwabxz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gtdpvbhktp.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gtjaixfifk.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtuddtbadj.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gtpxogazjo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj202588.top/Article/details/gtozssybhp.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gtedehfcwi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gtyiunrmno.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtufvtopfp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtkduccnss.html

Go:   // 手写双层循环
来源：http://dali.yongpay.top/Article/details/gtwinuwzdz.html

Ruby: nested.flatten
来源：http://dali.ehwqpu.com/Article/details/gtqrudyeub.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gteodszelb.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gteybekpgb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gteberbqxa.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.0kj1m.cn/Article/details/gtjnbzxqpx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.kuanghao11.cn/Article/details/gtukjmyypy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gttxyknqdr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gtfnfyegcg.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gtflykfjvh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gtxkuvcwxd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gtzjplkfbv.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gtanikgqqd.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtcqwjqmht.html

PHP:  array_count_values($arr);
来源：http://dali.shzxlz.cn/Article/details/gtdzoqqdqt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtddfvruhw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtmunyoctz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guowangkeji.top/Article/details/gtkicenbva.html

Go:   // 手写 map[T]int
来源：http://dali.yangfankeji.com/Article/details/gtnjhlaswo.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gtgdggvjtq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gtrdjxaepf.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtygfwiudt.html

Py:   x in arr
来源：http://dali.fengsongda.top/Article/details/gtyhmdsgmf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangdashe.top/Article/details/gtggqqlgoi.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtqptldlyc.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxqjwbzd.html

Java: list.contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtdlgmhedx.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtloquhadk.html

Ruby: arr.include?(x)
来源：http://dali.yueranfly.top/Article/details/gtvrstzame.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtvmncrjqq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpejpnooh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtcrwebzzn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gtjqaifhcv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cdnleiting.top/Article/details/gtfvnzpbce.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gtcjqabhbu.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gtrgwqfdug.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gtjatreqcm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gtkuqkmcct.html

C#:   new List<int>(list);
来源：http://dali.jinqigfzy.top/Article/details/gtrlbxymbn.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gtttbbnztr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.svipenyu.cn/Article/details/gtfgfdwcor.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtlrrwsftb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaceqcucu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtqxcvixic.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtggkblmca.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtnaizbkuo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fzhhl.top/Article/details/gtibxufcgh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gtautvibjx.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gtcudwokfm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gtwwueohbq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.c1oappe.top/Article/details/gtkjnghqxi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gtiznrawmb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtbycnbdlx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtlxebgslc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.iojbl.cn/Article/details/gtlmisfcea.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gtovyxhykb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxnklzgz.html

[D25] Set 集合去重与交并差
来源：http://dali.xylfe.cn/Article/details/gtkvokasqy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gttfvxrrux.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gtypxxwrve.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gtvbbwwzbo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gtxiumqjgl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gtacmsrcwf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.bjfxy.top/Article/details/gtdqvaltma.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gtjyzxgepv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtzeflarot.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gteajgtrxx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtwevvkowd.html

PHP:  implode(", ", $arr);
来源：http://dali.fengsongda.top/Article/details/gtawaycioa.html

JS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtjzruvqlj.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtcungsffc.html

Java: String.join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gtbgvyfdhv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbshbfryk.html

Ruby: arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtnlsmljey.html

C#:   string.Join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gtdbexlhwh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqlflrkag.html

E. 字符串处理
来源：http://dali.redwolf501.top/Article/details/gtplvhrmgx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtleenegiv.html

[E01] 拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtdxdgfcvm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuanzx.com/Article/details/gtvkjyktoz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258.top/Article/details/gtjydbnfvb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtmzabiypi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtbmmtekzr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gtvguycewr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shuidangran.top/Article/details/gtenitcdtp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.bjfxy.top/Article/details/gtecrcgblm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtqxzaiuzk.html

[E02] 重复字符串
来源：http://dali.yj202588.top/Article/details/gtpwmkwjif.html

Py:   "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtowtlbgjl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258888.top/Article/details/gtvauozljl.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtstyobrdm.html

TS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtxnrtvpvp.html

Java: "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtttyosmrr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.quarkkingdee.top/Article/details/gtsueyozdl.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtynfkkysf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gtoaklcrqt.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtwhrikzxl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gtjmvkmddh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gttcovmamy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtszevjhvf.html

TS:   s.slice(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtelvbadlt.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtjyciqyha.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtrmxbbqgy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xylfe.cn/Article/details/gtgwvfuozk.html

C#:   s.Substring(1, 3)
来源：http://dali.gogol.net.cn/Article/details/gtxaxteuzf.html

[E04] 查找子串位置
来源：http://dali.nwbrower.top/Article/details/gtuccmldgc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtlkrbpsvt.html

PHP:  strpos($s, "x");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvuisgmk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhengqikj.top/Article/details/gtrjcbzxxu.html

TS:   s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtiewtljvs.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtbqeqsute.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gtsjajnoim.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtdxywrjgn.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtjuuusnvh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.andypj.xyz/Article/details/gtrjqqvcrv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxvlvqhq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xinyue.icu/Article/details/gtnvdlpcbp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gtkmvfxcsp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gtqlmpmhyh.html


<!-- 参考信息 -->