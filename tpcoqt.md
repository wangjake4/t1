代发 wailian999

[C14] 泛型函数
来源：http://dali.wangshuangyany.cn/Article/details/gtonqtxruq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhixingplan.top/Article/details/gtjuksytyc.html

PHP:  // 无泛型
来源：http://dali.cheryme.top/Article/details/gtvsgpondv.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtidpsuamc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.316326.xyz/Article/details/gtlhgtqqog.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sxryk.cn/Article/details/gtaierqhyi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gtibfbfalr.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtbunoexll.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gtyfjsdmkk.html

[C15] 解构 / 展开参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfvgdoek.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gtfaxkhbki.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gtsjnbampk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtgfhnbcts.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gtkcxdqskz.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtpeiolcjn.html

Go:   // 无解构
来源：http://dali.daria6918.cn/Article/details/gtbihfqwnf.html

Ruby: a, b = pair
来源：http://dali.dashuyun.cn/Article/details/gtvwmxigej.html

C#:   var (a, b) = pair;
来源：http://dali.cucudq.cn/Article/details/gtwwwlxsve.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gtbztsxwxx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gtvliwdwhs.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gtwbnezaau.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yanxiufei.cn/Article/details/gtcwwauuew.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cqqwz.cn/Article/details/gttdsokmyz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gtcauggctj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zdqjudy.top/Article/details/gtqqwfdypq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gotoacloud.top/Article/details/gtryslwdcf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gzhubu.top/Article/details/gtwfnktoxs.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtgyzdquxt.html

D. 数组 / 列表 / 集合
来源：http://dali.aizwys.cn/Article/details/gtxufdcfjl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtsbidwdog.html

[D01] 创建数组 / 列表
来源：http://dali.havefunace.top/Article/details/gtgrnnohra.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.316326.xyz/Article/details/gttyjgzpan.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gtxsvaphyk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtbqgsyssi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gtxxuaokpm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hysaishi.cn/Article/details/gtwezqiscv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gtlwgtyoiw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gtqxhuyeds.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.bjfxy.top/Article/details/gtvszligsf.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gtvoostdre.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gtetginmsn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gtyvfrrenf.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtnvfoqqlq.html

TS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtkgptmtky.html

Java: list.add(4);
来源：http://dali.zhengqikj.top/Article/details/gtjzuscoef.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtztekdajg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtktonglqh.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gtssqqupdt.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gttfylervo.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gtenuxpzpa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gtmxjukzjc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtbvqlwrzs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cucudq.cn/Article/details/gtlwgvhkkz.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuqmepmj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtbxblopwc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cucudq.cn/Article/details/gtiwxhmlyo.html

C#:   list.Insert(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtjcivufjh.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gtkfwftwkd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gthpuvepgy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gtymhqwagv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daxiang520.top/Article/details/gtdqhdpgcy.html

TS:   arr.splice(0, 1);
来源：http://dali.yuanzhike.top/Article/details/gtoqsnoqic.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gtxzbjubff.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gtksjebgrh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.bjfxy.top/Article/details/gtlzqmmjay.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jianghu66.top/Article/details/gtcyrwagiq.html

[D05] 访问与修改元素
来源：http://dali.yonumen.top/Article/details/gtojfganff.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtloovtvpx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtjfttvthy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gttwusspfz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtejpjstjw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigfzy.top/Article/details/gteaqaroyd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtuuqdbjhe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtitovipbf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtkqjrzplb.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gtmeikkqct.html

Py:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtwonjbdoo.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtrxlohawn.html

JS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gttgqoloxr.html

TS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gtwgosaxub.html

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gtlokcprdm.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtxpuezqdu.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gtifrlkkir.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gtcyiroysj.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gtkghhlppu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.snrcjt.cn/Article/details/gtepoisbpy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtnviujhyo.html

JS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqadmxgi.html

TS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtssgisyxj.html

Java: list.subList(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnpbghup.html

Go:   arr[1:4]
来源：http://dali.yangfankeji.com/Article/details/gtkibxssna.html

Ruby: arr[1, 3]
来源：http://dali.tanke756.top/Article/details/gtmjkxcpao.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gttomnlpfn.html

[D08] 合并两个数组
来源：http://dali.chenlongwang.top/Article/details/gtcnbgcouz.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gtvasbavnp.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gtehusyjen.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.feifeiyinyue.top/Article/details/gtpunjbfox.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtboryfhmc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgfzy.top/Article/details/gtepxaazcs.html

Go:   append(a, b...)
来源：http://dali.wangshuangyany.cn/Article/details/gtgknzzago.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gtgifniyhs.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtyvwczzly.html

[D09] 排序（升序）
来源：http://dali.hnqzz.top/Article/details/gtyhrohpce.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtrrljityj.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gtehltcdqd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gtvdrnsdrm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sxryk.cn/Article/details/gtyywtdbhw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.smart0.xyz/Article/details/gtsdgqkfkb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gtmcfoxugc.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtvvarvkwa.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gtauicpkra.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gtorrhaszb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gtnlcoxllz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gtaroplimz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gteciyaowo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gthipnoxbt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgufenzy.top/Article/details/gtgcpvdwuy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gtregiimey.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sxryk.cn/Article/details/gthgvnepcx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.vqdsnc.cn/Article/details/gtvubtrrbh.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gtideuqucp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhengqikj.top/Article/details/gtubpxjylq.html

PHP:  array_reverse($arr);
来源：http://dali.andypj.xyz/Article/details/gtnnpjeazs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dashuyun.cn/Article/details/gtrrhavhrb.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gtyhcnkqwx.html

Java: Collections.reverse(list);
来源：http://dali.316326.xyz/Article/details/gtdgpjjjfd.html

Go:   slices.Reverse(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaibnjlnv.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtuujkccaw.html

C#:   list.Reverse();
来源：http://dali.chenzaomai.com/Article/details/gtncgbowqm.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gterrfojba.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gttsohfwyu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gtuexpeavg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtecdhqxny.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gtblcdjpvl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnqzz.top/Article/details/gtvyjkyvxw.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtlwfyakgv.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gtplrchdfi.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gtqdvwkigh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cqqwz.cn/Article/details/gtywwdsozc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gtccypqoqp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.bjfxy.top/Article/details/gtcyufzitt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtdzkutlfn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtawwruexr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtwhhthnmc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gtdfodjptn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guannengcc.top/Article/details/gtxusyvxfq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtzvpbvtxb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gthhxozfvi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gtvtpwihjc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtjwjjyixc.html

JS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtgktdkdyl.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxutgbfju.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gtdxvmejcw.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gttukukpuc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cashguo.top/Article/details/gtzgdjwtua.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gotoacloud.top/Article/details/gttyameezy.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gtmwvutlip.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gtikjwnqtm.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamaqqxuc.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtqsikalwg.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtjyedgmat.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenzaomai.com/Article/details/gtwuukrtsp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gtcchuezwb.html

Ruby: arr.uniq
来源：http://dali.yj20258.top/Article/details/gtbvyobwqi.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gtkczykxfi.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gtgpoiefvo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cheryme.top/Article/details/gtefrgahsq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtkkbjwnyf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtzqdlggmh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtrpfktohu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gtnkipfjxf.html

Go:   // 手写循环累加
来源：http://dali.snrcjt.cn/Article/details/gtinzbmxqn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuxming.cn/Article/details/gtyxwntbqr.html

C#:   list.Sum();  list.Average()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthprjhcew.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gtngzkrdiu.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gtaccomdpi.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtpriimpds.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangdashe.top/Article/details/gtvxmccxnq.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gthetcygjc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkubzjab.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gthvhrpkte.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gtrulaelen.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtuakuladj.html

[D18] 扁平化嵌套数组
来源：http://dali.tianlin.xyz/Article/details/gtccnswqmg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtdfdybkum.html

PHP:  array_merge(...$nested);
来源：http://dali.yuxming.cn/Article/details/gtubccvyjd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cheryme.top/Article/details/gtbutfbdxy.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gtpbzrdcva.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gtrzomrsts.html

Go:   // 手写双层循环
来源：http://dali.pengpengdd.cyou/Article/details/gtyvksxyit.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnwxovge.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtvmlfxxpk.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gtbntmksox.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.birdmap.top/Article/details/gtmhigyipl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkyvgubl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.svipenyu.cn/Article/details/gtzaqlfbin.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtemhgfkww.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtvgweajyh.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gtxengqoyq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daria6918.cn/Article/details/gtzgemfpkv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtzltadgbq.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gtarwpczse.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gtebfyddww.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gtdnsioefx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gtrfrdytcc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtnppquahv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gtcexcfpda.html

Go:   // 手写 map[T]int
来源：http://dali.shuidangran.top/Article/details/gtihkftqmu.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gtpxsdjzro.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gtvsguatab.html

[D21] 判断是否包含某元素
来源：http://dali.tianlin.xyz/Article/details/gtofxsubei.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gtawwdyavx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtdmsviuob.html

JS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gtqgrpxrlf.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthsxptfc.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gtjzifnnku.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtxxsjplbq.html

Ruby: arr.include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtwdyylkrn.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtnswziomc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenlongwang.top/Article/details/gtikoeazfv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtunqjkaxq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gthwgjymqo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gtsknpyhte.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gtajycybij.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gtsdwwsivu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gtuqnddxry.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gtmogoqpoj.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtglbtgnce.html

[D23] reduce 累积计算
来源：http://dali.jiagoushi.top/Article/details/gtpyainzcc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ivvv.top/Article/details/gtujpkehap.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fzhhl.top/Article/details/gtirblulxn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtncxpdmxd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtbnjbnxyp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gtgkivgiao.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gttkivrqmv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gtzmhnegey.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gtmfxahepw.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gtfoxtehal.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhixingplan.top/Article/details/gtxhabzbkr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pycfn.com/Article/details/gttexgzrvj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtwnrxdajm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtltysqxng.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gtrwmjunyp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gtkaienhey.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gtsuguqomn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gtvnilsgrm.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gtmsixjved.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gtxvenolyv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cheryme.top/Article/details/gtrgrrfeea.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gtxqfjfemp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yanxiufei.cn/Article/details/gtyhnzgltd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gtnhjxnphj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gtttouhgwd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gtekfdkpzk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cheryme.top/Article/details/gtvcosbodb.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gtibcxhtku.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gtxxlqxgyb.html

PHP:  implode(", ", $arr);
来源：http://dali.ppjwa.cn/Article/details/gtnhxbvzll.html

JS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtmmbudkmm.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtdvqbayto.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtnfbtnlxg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gtsfnpwqez.html

Ruby: arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gttxjgsvzf.html

C#:   string.Join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtporxhzjr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvblssmvh.html

E. 字符串处理
来源：http://dali.pycfn.com/Article/details/gtrtqpaioe.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtvqndvrgq.html

[E01] 拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtsgynntug.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jiagoushi.top/Article/details/gtkxnihppn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.havefunace.top/Article/details/gtrrmwkqzs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtwzrrwche.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtcgghcifi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jlsjyb.cn/Article/details/gtwfykbyrw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbtsxeom.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gtgbmikrpu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtxpbwxeki.html

[E02] 重复字符串
来源：http://dali.chenzaomai.com/Article/details/gtfkqqruft.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtfehgkjhg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gtsdhdlill.html

JS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtgtmiyiuc.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtacdsxhkz.html

Java: "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtjjufoqws.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258.top/Article/details/gttyxuwfam.html

Ruby: "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtnqzqyyjl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gtqnbckdfk.html

[E03] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakkumldi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gtwwfoifnh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcaisvqmg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtjnwgihij.html

TS:   s.slice(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtciqtjtyo.html

Java: s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtjudupcld.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ivvv.top/Article/details/gtnggfpkrv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xziqi.cn/Article/details/gtnnvwvzde.html

C#:   s.Substring(1, 3)
来源：http://dali.hysaishi.cn/Article/details/gtkiptwehe.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gtprkrtykk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtrlglrukw.html

PHP:  strpos($s, "x");
来源：http://dali.ehwqpu.com/Article/details/gtrrepjkbl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtenoechmg.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gttfyqmdje.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtduxldzle.html


<!-- 参考信息 -->