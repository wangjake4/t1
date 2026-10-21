代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gtyubffzsb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ydzc1.top/Article/details/gtjipkewsz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gtabhmfhga.html

Ruby: # 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtaajimklv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gtiozhvdzt.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gtzeujbzdp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gtzaeezktf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cdnleiting.top/Article/details/gtqfzicqgh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvejqylkn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtumhhcpxb.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtqjeyqloc.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gtilzxbthl.html

Ruby: a, b = pair
来源：http://dali.jqgfzy.top/Article/details/gtldodtgfv.html

C#:   var (a, b) = pair;
来源：http://dali.wangdashe.top/Article/details/gtjkoqgidi.html

[C16] 函数 / 方法重载
来源：http://dali.jqgfzy.top/Article/details/gtqpyatnsl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtaqgzdrmy.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gtejifndue.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gtdknfohrn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gotoacloud.top/Article/details/gtfgkygasz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gtytfllpds.html

Go:   // 无重载：用不同函数名
来源：http://dali.fengsongda.top/Article/details/gtqpoengiy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gtvcselfwz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gtucguncas.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqwqivnnz.html

D. 数组 / 列表 / 集合
来源：http://dali.hammf.cn/Article/details/gttawykatm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtmaowtgyu.html

[D01] 创建数组 / 列表
来源：http://dali.nanxinkj.top/Article/details/gtwqtsloqu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gtsujvdnpj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gtcyzjzzkc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xziqi.cn/Article/details/gtsvzhgmcn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jianghu66.top/Article/details/gtidgbfbhr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gtudcxcuzw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gtjxmilkhj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gtkiluqaeq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.iojbl.cn/Article/details/gtvirenrce.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gtxhfozdhh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tanke756.top/Article/details/gtowcczqvu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtloldiazv.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gtdrvvssvf.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtbkpcbgxp.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gtnlmqnddk.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gtuhshnfom.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gttxzwtqgu.html

C#:   list.Add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtvlymeqvh.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyedzivju.html

Py:   arr.insert(0, 0)
来源：http://dali.ppjwa.cn/Article/details/gttyafntzg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ivvv.top/Article/details/gtlelxpcqo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gtiaglmpuq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ivvv.top/Article/details/gtlvtmvcxo.html

Java: list.add(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gttuncfmrz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtjahxzelv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cqqwz.cn/Article/details/gtfoyrcamt.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtvapexnao.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtblpzvuxh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.bjfxy.top/Article/details/gtyxxeoknh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gttaruedyc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gtsnnobtyf.html

TS:   arr.splice(0, 1);
来源：http://dali.xinyue.icu/Article/details/gtemvvsvre.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gtjsaccwzd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gtsojauoss.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sxryk.cn/Article/details/gtogkiancj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258.top/Article/details/gtdopfljco.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gtcgshftgc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtcbigrexb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtwiuibhjo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtnpotlwvv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ydzc1.top/Article/details/gtyqgokusz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxuanxn.top/Article/details/gtfxjlofkk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtmzllmwma.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtfqansmng.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtcsplujch.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtqwpeqbvz.html

Py:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gtemivqtol.html

PHP:  count($arr);
来源：http://dali.yj202588.top/Article/details/gtimdwqpto.html

JS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gtduugbimk.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtswafpqkz.html

Java: list.size();
来源：http://dali.yonumen.top/Article/details/gtgxmaihgf.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtwgdtiooo.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtpvcakiht.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gtdbkbuvay.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gtvygeevab.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.andypj.xyz/Article/details/gtgqzgymth.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ivvv.top/Article/details/gtoeszdvcm.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtgtwtucaz.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtmcakhgqz.html

Java: list.subList(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtfpmzalgp.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gtanwshilp.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gtzxuyngwh.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtssqxomsy.html

[D08] 合并两个数组
来源：http://dali.kuanghao11.cn/Article/details/gtiggxwxzn.html

Py:   a + b;  a.extend(b)
来源：http://dali.jianghu66.top/Article/details/gtuhpnvald.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gtbntgojxp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ivvv.top/Article/details/gtvhvwpsmp.html

TS:   [...a, ...b];
来源：http://dali.zhongyouzk.top/Article/details/gtwjkmiqsw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gthkmuczsx.html

Go:   append(a, b...)
来源：http://dali.yuanzhike.top/Article/details/gtpadlmuww.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gttrqxqfcr.html

C#:   a.Concat(b).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtnllzkjwu.html

[D09] 排序（升序）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnplipnf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtwugzmibq.html

PHP:  sort($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflxjuvti.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sxryk.cn/Article/details/gtpowkfzys.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnqzz.top/Article/details/gtliyeuyir.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.haohaochexian.top/Article/details/gtjygnfuwe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtympvidab.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gtfxwdwpts.html

C#:   list.Sort();
来源：http://dali.yueranfly.top/Article/details/gtohhpfxsq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gtvavfklii.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gtrlsgscli.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtbndwpuru.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gtjjkyjrin.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtrzwooabo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yongpay.top/Article/details/gtkrviraop.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cucudq.cn/Article/details/gtfocluubz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gtyagdrqra.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnqzz.top/Article/details/gtjdtwsima.html

[D11] 反转数组
来源：http://dali.nanxuanxn.top/Article/details/gtslbpmhwx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gtnpfjfxkl.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gtfqanqbma.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pycfn.com/Article/details/gtslgdzaiz.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtrsmmsxkp.html

Java: Collections.reverse(list);
来源：http://dali.chenlongwang.top/Article/details/gtindwutmn.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gtkvvjfbua.html

Ruby: arr.reverse
来源：http://dali.daria6918.cn/Article/details/gtktmlisfp.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gtkhcgdlhv.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gtfzyeanfg.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gtcehoefav.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtudwhkzaa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtxbdznmcs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gtuvdzlvfm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xinyue.icu/Article/details/gtcrefhgjr.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gttjybpseh.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gtuxuiryqy.html

C#:   list.IndexOf(x);
来源：http://dali.wangdashe.top/Article/details/gtghowefaw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gteeeuhlae.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gtayvbtjxv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gtailawoni.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvcjszae.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtzybbvngy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gtuwjsulrx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sxryk.cn/Article/details/gtmqrdzbdr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xinyue.icu/Article/details/gtxfuykkjf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtsgasliav.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtglzncahy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gtpxzlhqaq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gzhubu.top/Article/details/gtltmjroui.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtahtgfaix.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtrhcdkekg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnumhoxtn.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtpbsoyuvk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gtawvhjmte.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hammf.cn/Article/details/gtglzpbxhp.html

[D15] 去重
来源：http://dali.guowangkeji.top/Article/details/gteqxqxtkc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gtrjcyvyjq.html

PHP:  array_unique($arr);
来源：http://dali.zhixingplan.top/Article/details/gtqbjoepjf.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtjphsecys.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtgpewlzvk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.kuanghao11.cn/Article/details/gtlagdgjsx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gtjtvwhjyv.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gthnhgaxrz.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtqtyfkmfz.html

[D16] 求和与平均值
来源：http://dali.aibaodan.cn/Article/details/gteqejmrdb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtbojvdnza.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtjncxmszi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtubnrjtoh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtxvdoifcs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yueranfly.top/Article/details/gtudpcqtwn.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwlkdfyl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtegdcvgkx.html

C#:   list.Sum();  list.Average()
来源：http://dali.ydzc1.top/Article/details/gthrlbfjql.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gturqswxei.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtfvvzlmfz.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gtfeyfhlnl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jianghu66.top/Article/details/gtmqnmwdli.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gtujotcvct.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gttbofylcm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gtrvucxaon.html

Ruby: arr.max;  arr.min
来源：http://dali.hysaishi.cn/Article/details/gtiyqvnefg.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslwkrnvw.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gtqkwjwedf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gtivxwuada.html

PHP:  array_merge(...$nested);
来源：http://dali.shuidangran.top/Article/details/gtgqoahnqj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gtpoutpwqs.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtqbqomoam.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrckkcdv.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtjdosbjee.html

Ruby: nested.flatten
来源：http://dali.xinyue.icu/Article/details/gtsoncqhaf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gtuvicpwei.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gtpuectrhl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gtnvvucnqp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.kuanghao11.cn/Article/details/gtgcpcfqry.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuanzhike.top/Article/details/gtdfqapmvk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtlohamkkv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aizwys.cn/Article/details/gtehqmyntg.html

Go:   // 手写 map[string][]T
来源：http://dali.pengpengdd.cyou/Article/details/gtjwtqhefs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gtavbjcccp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gtfrephkik.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gtkcfcxail.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gtuhyjtnbn.html

PHP:  array_count_values($arr);
来源：http://dali.yj202588.top/Article/details/gtfgvegfge.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtbhmhtbgt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtpyfddbbz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gtsqspcboc.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gtnhksghxf.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtrbwkvize.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigfzy.top/Article/details/gthktlyplj.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gtgoldpjax.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gtmttxrhbv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtukckkydr.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtfsumnxyg.html

TS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtjmygctep.html

Java: list.contains(x)
来源：http://dali.ivvv.top/Article/details/gtugghjznd.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtsbphdydf.html

Ruby: arr.include?(x)
来源：http://dali.cucudq.cn/Article/details/gtgloxpxym.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtzwmahtoz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gtqvddpztp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuanzhike.top/Article/details/gtdivmzcxy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gtcsdarcns.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gtoxrsagqs.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gtoleltczi.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrufkwei.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.iojbl.cn/Article/details/gtffrmspqo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangdashe.top/Article/details/gtrnpaozuj.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gtujulupjr.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gtvmwnrvka.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtvvotxpgt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gtoacikxqd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlcmsahz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtjqayrmmh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhongyouzk.top/Article/details/gthkxtlobd.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtrxmvyejq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.0kj1m.cn/Article/details/gtfttwrojt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ivvv.top/Article/details/gtuengiwlz.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gtzulwifkv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gtnskyqmhh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.iojbl.cn/Article/details/gtahfbywxk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijcwbeyg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtsjhwrdpg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gtecaflmho.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtstfsodrc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.havefunace.top/Article/details/gtyronmvpg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yongpay.top/Article/details/gtxlzcvowk.html

[D25] Set 集合去重与交并差
来源：http://dali.316326.xyz/Article/details/gtrzlznunt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gtohdehjkh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gtntnajskw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gttzymxvva.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtusoqfxtp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtpnyybknx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gtiyneyzex.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gtljctxgzx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gtopnsfgpv.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtkbrsoira.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtaczwlaqu.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtsggapgjr.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtnycariea.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gttgutczxe.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtltetdaxg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gtootiibwg.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtllxdtjyw.html

C#:   string.Join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtjuwohxcx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtghfwclpv.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gtxliawstv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtvcgmvpcp.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtdfpfgafi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jiagoushi.top/Article/details/gtfweuxnwl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gtroayqxzi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gthyqwhifo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gtjwlffpvo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pycfn.com/Article/details/gtdhdifdij.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnqzz.top/Article/details/gtiwqbfssd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhixingplan.top/Article/details/gtlgisxchg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtdvdhpola.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gtkrltworx.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtkuqktlvb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258888.top/Article/details/gtpujbosqc.html

JS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gttwzlweag.html

TS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtugvmyvbk.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmiwdihu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyhsqxgu.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtfoknpglp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tianlin.xyz/Article/details/gtftepeugf.html

[E03] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtthtggxpr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gteqyrsbpq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtizpewbaf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtociemeam.html

TS:   s.slice(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtsxoboqpq.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtknngrwrn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cucudq.cn/Article/details/gtysjryyea.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpqoowyb.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcoxvsdq.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gtphnkwbjw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gtyscistch.html

PHP:  strpos($s, "x");
来源：http://dali.chenzaomai.com/Article/details/gtjjwzxjnx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.smart0.xyz/Article/details/gtwudcwjcc.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gttnmiuwmp.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtzhuyiuvs.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gtpaksambz.html

Ruby: s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtekwjdesq.html

C#:   s.IndexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtachqdfng.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhiwuduotai.top/Article/details/gttbmrmbgo.html


<!-- 参考信息 -->