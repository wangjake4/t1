代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gtfxmuxnaj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrznwdof.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gteizqqtld.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gtfqpejxmi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtkuooiusu.html

[C15] 解构 / 展开参数
来源：http://dali.sweek.top/Article/details/gtlnfevkev.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gtsflbbtzl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtzxcotfkv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gtchfkzjas.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daria6918.cn/Article/details/gtbgrmppau.html

Java: // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtfbcqpeht.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gtcuelvyxa.html

Ruby: a, b = pair
来源：http://dali.havefunace.top/Article/details/gtxgftumpk.html

C#:   var (a, b) = pair;
来源：http://dali.mhx1999.top/Article/details/gtecvkklao.html

[C16] 函数 / 方法重载
来源：http://dali.nwbrower.top/Article/details/gthrxattjh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xylfe.cn/Article/details/gtcqexnqzg.html

PHP:  // 无重载
来源：http://dali.meibo888.top/Article/details/gtgfrdoknh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gtvugfmajn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gtvitymsil.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zdqjudy.top/Article/details/gtfmukxyxe.html

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gtfumvzrcw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zdqjudy.top/Article/details/gtylznbtjw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtiwxtmdzq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxacpawfs.html

D. 数组 / 列表 / 集合
来源：http://dali.daxiang520.top/Article/details/gtmvncpdmw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtgvbhsoia.html

[D01] 创建数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gtnhydnbdq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.0kj1m.cn/Article/details/gtxcweslhd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gtrsqycorp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gttodarqie.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ppjwa.cn/Article/details/gtrfvdrxht.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gtmjfscrrb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmadjzlrp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtcoxuecdx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gttaodbvmt.html

[D02] 追加元素到末尾
来源：http://dali.pycfn.com/Article/details/gtjdzsqyak.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqxszxkq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xylfe.cn/Article/details/gtlwvwtfkc.html

JS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyoteowvs.html

TS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtmkneyicj.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gtdzdbmasz.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gthcqbawoo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuxming.cn/Article/details/gtslkyquhu.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gtfsozbvps.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gtescajyca.html

Py:   arr.insert(0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtdzghvnro.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gzhubu.top/Article/details/gtlqhiwwub.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gtlgcugkdg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gtykbfwlmk.html

Java: list.add(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtxlpmbuhw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcrcongo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnxiangtu.top/Article/details/gtngutfoqu.html

C#:   list.Insert(0, 0);
来源：http://dali.ydzc1.top/Article/details/gtsfimyeds.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gtcgxbljnz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daria6918.cn/Article/details/gtcpasgibd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xziqi.cn/Article/details/gtbpzrusfs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gtixbfxrfa.html

TS:   arr.splice(0, 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtekjsulvo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gtzpwlnkme.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gtdauklqba.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sufxvd.cn/Article/details/gtakfklnlz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shzxlz.cn/Article/details/gtfscudjee.html

[D05] 访问与修改元素
来源：http://dali.bjfxy.top/Article/details/gtxvlplkmr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtifebgbsy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtqtwspaqt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtqsddlwxu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dashuyun.cn/Article/details/gtbeinvnhv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gtaisafkyu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtwhhcfbwu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtytzzmppt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtggpzmeor.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtfkurnfhp.html

Py:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtdstbdgsc.html

PHP:  count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtjjzmbppc.html

JS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtxjxpbaat.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtxaazjbgb.html

Java: list.size();
来源：http://dali.jqgfzy.top/Article/details/gttmtagvsu.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtzjqqqqhe.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgigqwoc.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gtrdudwqtb.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gthtojypma.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258.top/Article/details/gtpluqlzye.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guowangkeji.top/Article/details/gttnfqvvdn.html

JS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtnoumhjtg.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtnixrsqio.html

Java: list.subList(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtwnqevzft.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gtfykaizsl.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gtvigprxzp.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuanzx.com/Article/details/gtagrjqeub.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gtgiscohjc.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gtliznppkz.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gtqxzoxhpy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hammf.cn/Article/details/gtpmkrgqev.html

TS:   [...a, ...b];
来源：http://dali.yanxiufei.cn/Article/details/gtwuqumcga.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zdqjudy.top/Article/details/gttofewvsb.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gtnefvrjnr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sweek.top/Article/details/gtfpnhjtqk.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gtpawelwlw.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gtmfugekjz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtrjecszuv.html

PHP:  sort($arr);
来源：http://dali.hfpthk.cn/Article/details/gtazudmott.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.iojbl.cn/Article/details/gtbnhghrzi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gtvvdwvbsp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigfzy.top/Article/details/gtjjvaygdl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gtfbzybaqa.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtmcoqvagx.html

C#:   list.Sort();
来源：http://dali.cdnleiting.top/Article/details/gtuxfahxcv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtstytjama.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxinkj.top/Article/details/gtoexzidkh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gthzbdbztr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gtslwmsewp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gthdzwotab.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gtonhrvfpk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gtzpjerifm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtommkxlea.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shuidangran.top/Article/details/gtgwmaloth.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gtaakaqfnj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gtlzsgkgus.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtvwagdlzz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gtimewdpuw.html

TS:   [...arr].reverse();
来源：http://dali.shuidangran.top/Article/details/gtlyilhrgj.html

Java: Collections.reverse(list);
来源：http://dali.hywenlv.cn/Article/details/gtapyoyosq.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gtqldfkyzs.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gtzpdefbgl.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gtvxgyonct.html

[D12] 查找元素下标
来源：http://dali.shangyingyoupin.top/Article/details/gtazqgofoz.html

Py:   arr.index(x);  x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gthzlafyap.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nwbrower.top/Article/details/gtmrwljacj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtokypnoot.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtzoxaydzw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sufxvd.cn/Article/details/gtwnuslemj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtrfllnjth.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtuindhgib.html

C#:   list.IndexOf(x);
来源：http://dali.sufxvd.cn/Article/details/gtbpnuiqid.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnxiangtu.top/Article/details/gtlmglgznz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtlnqsygdm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nwbrower.top/Article/details/gtbfvvlaad.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtvrxyjwrk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtyauenucd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gtphjsrsxf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ydzc1.top/Article/details/gtswrieklm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenlongwang.top/Article/details/gtgobsyqit.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gtnpsaldon.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbjwicpx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtmyapwibk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.meibo888.top/Article/details/gttluggpfu.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gtuzkgbgpc.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtggmyvadk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gttzbqlvho.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gthgykuygt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtpzlmqteu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtaumcbwbn.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gteryiqnkm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gtsunyjhii.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gtjwhezaab.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtsexuzdlw.html

TS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtiyjhhsmr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gtbgchazyj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangdashe.top/Article/details/gtenihnoed.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gtqgxfxsys.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gtejgfdnrq.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmslppscg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hysaishi.cn/Article/details/gteircrrne.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ehwqpu.com/Article/details/gttozzqnrz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtlicemwrz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtowosdoeq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hfpthk.cn/Article/details/gtkwwzdimh.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gtdmbekrjl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtwkesedqu.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgwxbdmk.html

[D17] 最大值与最小值
来源：http://dali.sufxvd.cn/Article/details/gtbvkhmjoy.html

Py:   max(arr);  min(arr)
来源：http://dali.havefunace.top/Article/details/gtlucnwrpn.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gtntqtasoh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gteuteuxid.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gtsafjadtg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gtqnkpywju.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gttlhhhjdl.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gtohawbvsr.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gtowbatzne.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gtnsxuxakj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jianghu66.top/Article/details/gtssrwxshz.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtemeotecf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gtwtnwtlru.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtzghptwph.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtidwtmbpc.html

Go:   // 手写双层循环
来源：http://dali.jqgufenzy.top/Article/details/gthaxsqlsy.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtjigqtsyl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtcwdyrhdh.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gtmcojwnqa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daxiang520.top/Article/details/gtbkejzunw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gtzkcbtjde.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gtadwjjnmj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gtcwxwnzms.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hywenlv.cn/Article/details/gtgqolgwby.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gtelakveoa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbseaxjje.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gtqqnklddg.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gtzqwfavsz.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtdblwecym.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gtlgmheotf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtueerynrf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtbupvjjnn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gtrrlhvmvj.html

Go:   // 手写 map[T]int
来源：http://dali.cucudq.cn/Article/details/gttyahbdgd.html

Ruby: arr.tally
来源：http://dali.yongpay.top/Article/details/gttidmsycv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.redwolf501.top/Article/details/gtjqysqmol.html

[D21] 判断是否包含某元素
来源：http://dali.redwolf501.top/Article/details/gtglhwfvnr.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gtkjoqewuo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtavjaulyi.html

JS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtbbliizwp.html

TS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtxvujzotl.html

Java: list.contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtguojbjzl.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtforqxfyn.html

Ruby: arr.include?(x)
来源：http://dali.nanxinkj.top/Article/details/gttrdmybyk.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gtyypaekgv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gtrbpkjlvz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gtjrkgqzrs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gtcdckgaes.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gtjdueioww.html

TS:   [...arr];
来源：http://dali.kuanghao11.cn/Article/details/gtojiuwfbo.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtmunlryym.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gtdtdrtsws.html

Ruby: arr.dup;  arr.clone
来源：http://dali.kuanghao11.cn/Article/details/gtvrcmgyzk.html

C#:   new List<int>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtptpbkyra.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiameukm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangdashe.top/Article/details/gtxzgsfzlu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gtbgwbxzno.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtvgwdwsfr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gthmhdmmhj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sweek.top/Article/details/gtcqegpqan.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtvwgwrxbi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gtunminand.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xylfe.cn/Article/details/gtoiqrhhwa.html

[D24] 字典 / Map 基本操作
来源：http://dali.hysaishi.cn/Article/details/gtfhxtkhgp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jyoumei.cn/Article/details/gtrlbzwhgm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gtpuekesmy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sweek.top/Article/details/gtzmkinrgv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtvtdcgnab.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shzxlz.cn/Article/details/gtdkujjunc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gtvzzmescg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.andypj.xyz/Article/details/gtlhkfpqvg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuxming.cn/Article/details/gtvewtxjph.html

[D25] Set 集合去重与交并差
来源：http://dali.quarkkingdee.top/Article/details/gteenkprrh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhgghdgr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gtaxpjuqxa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gtutcukwgs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gzhubu.top/Article/details/gtmkcccpye.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yonumen.top/Article/details/gtzrcckyin.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gtdyfvkxca.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlkumjas.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtaxiworyw.html

[D26] 数组转字符串
来源：http://dali.zdqjudy.top/Article/details/gtqjwoywye.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gttpdlular.html

PHP:  implode(", ", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtyvyannup.html

JS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtrchdgmjb.html

TS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtwwzkwrse.html

Java: String.join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtsvtprcmd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gtbrzdslny.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gthcvjfoce.html

C#:   string.Join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtfadchzhw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtaokqahyc.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gtodtvglyx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqogrtexv.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtffnryxcy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gtitzalhnp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gtpuvmfyey.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtpvwftlhk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gteurmccpz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gtdduhywrt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhoulong.xyz/Article/details/gtnqnvgpto.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtpezubifi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtiiqyexzf.html

[E02] 重复字符串
来源：http://dali.yj202588.top/Article/details/gtpwspaxay.html

Py:   "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtwpldujyy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gtgpodlbyq.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtjhvfudfq.html

TS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtdipgffnl.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtmruztedi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gtmtllsxfe.html

Ruby: "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtpwisrldw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gtogsohqtj.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtezrqxzqa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gtxptidtdg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtzenqyjtr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtltvxijxz.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gtippvsxnd.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbgawzus.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtjntabxmp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guowangkeji.top/Article/details/gtrlblbzzz.html

C#:   s.Substring(1, 3)
来源：http://dali.redwolf501.top/Article/details/gtinxusesk.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gtwmrhrmow.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtfzqsdbuv.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gtocpscwqg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gtyqtmjjvr.html

TS:   s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtmecenzee.html

Java: s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtxgwptepi.html

Go:   strings.Index(s, "x")
来源：http://dali.c1oappe.top/Article/details/gtvkhpidwi.html

Ruby: s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gtmxyxfudq.html

C#:   s.IndexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtfmkanscu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gtumgfgmwf.html


<!-- 参考信息 -->