代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gtgfjoobwt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtwkzckacb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gaohongyu789.top/Article/details/gtabxuzqtd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtrdhkdiga.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gttamqzmgu.html

Go:   func add(a, b int) int
来源：http://dali.yvedp.cn/Article/details/gtbaiefmmx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuetiantiany.cn/Article/details/gtkfcndhqz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.quarkkingdee.top/Article/details/gtufvrloir.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gtgrtjkmfy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xylfe.cn/Article/details/gttxshekzw.html

PHP:  // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtphseumdw.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtokqeksiw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gtpxajzvoy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gtmnyxxedu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gtiyqrfxnt.html

Ruby: # 无泛型
来源：http://dali.cheryme.top/Article/details/gtreloucmk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gtngfuvihu.html

[C15] 解构 / 展开参数
来源：http://dali.wangshuangyany.cn/Article/details/gtjnalpfyb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nwbrower.top/Article/details/gtmqylwxoq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cqqwz.cn/Article/details/gtjjbcbgfa.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gthrayqdzf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnqzz.top/Article/details/gtcigjinwq.html

Java: // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gtcstzebci.html

Go:   // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtwjgvhsmg.html

Ruby: a, b = pair
来源：http://dali.yj20258.top/Article/details/gtieoecycw.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gtljedrxbo.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtdimomeol.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gtwwmuxtht.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gtsszfjpxv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gtiulykoia.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtzzmgpqur.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.andypj.xyz/Article/details/gtkaylmegc.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gtzkvocrif.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhfuqnzd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gtolcyuvpd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtybmxujep.html

D. 数组 / 列表 / 集合
来源：http://dali.gzhubu.top/Article/details/gtbhblklet.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxfidosrp.html

[D01] 创建数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gtnjiawxiu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hammf.cn/Article/details/gtereonxhs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sysykeji.top/Article/details/gttifgwfkr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtlgkvppen.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.bjfxy.top/Article/details/gtstoogypz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gtbikpekez.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gtemieejvz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guowangkeji.top/Article/details/gtvsrpdyha.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gtsfdworuw.html

[D02] 追加元素到末尾
来源：http://dali.meibo888.top/Article/details/gtocoypble.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gttpadnmzz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gtjvfyirbk.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtdlzzgmmu.html

TS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtophrlyev.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gtalcnhhll.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gtijgbzmjq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gtrrouorav.html

C#:   list.Add(4);
来源：http://dali.yanxiufei.cn/Article/details/gttkzvhdoq.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gtjgbhqkcl.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtgjviuiic.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gttflsdtoi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhengqikj.top/Article/details/gtaspiqpem.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gttgezvzpn.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtxeqsgvrl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gtnhnbuyqc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuanzx.com/Article/details/gtjmgejijn.html

C#:   list.Insert(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtcniizlcf.html

[D04] 删除元素
来源：http://dali.gotoacloud.top/Article/details/gtcmelftyi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.vqdsnc.cn/Article/details/gtmssgvuer.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tianlin.xyz/Article/details/gtbgmuzbzw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.kuanghao11.cn/Article/details/gtqsjwyfhz.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtnqlqhhqd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gtpjhhgius.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhixingplan.top/Article/details/gtoswnjnvz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.haohaochexian.top/Article/details/gteohmjrdg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gtwrkykbxc.html

[D05] 访问与修改元素
来源：http://dali.9152youxi.cn/Article/details/gtlamxuads.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtrajeyozo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtfnqwjwkc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtstoctoho.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulxofjob.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yanxiufei.cn/Article/details/gtpxajhqax.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtrwhhttcj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtywigdhrt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gttwqcrcvg.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtcdqcajcv.html

Py:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtftcmjvbv.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtfdwtygor.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtuehmavaa.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnyzuswj.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gthehqilxl.html

Go:   len(arr)
来源：http://dali.yongpay.top/Article/details/gtlghbfhnp.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gtjwpxoybq.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gtfwdnelvy.html

[D07] 切片 / 取子数组
来源：http://dali.pycfn.com/Article/details/gtlpjgdisl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gtjnpimjqh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtycgtfpde.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtexegauky.html

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtiktfgplq.html

Java: list.subList(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtldhymjqx.html

Go:   arr[1:4]
来源：http://dali.jinqigfzy.top/Article/details/gtjiunrrmy.html

Ruby: arr[1, 3]
来源：http://dali.xinyue.icu/Article/details/gtpqjxlbxr.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gtxjomexhr.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gtuibmtdew.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnqzz.top/Article/details/gthuzjtuqt.html

PHP:  array_merge($a, $b);
来源：http://dali.wangshuangyany.cn/Article/details/gtqtpijjcr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigufen.top/Article/details/gtlgujuzkc.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gtbwlgtqxm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj202588.top/Article/details/gtyiarzatd.html

Go:   append(a, b...)
来源：http://dali.xinyue.icu/Article/details/gtyukkdesl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gtbefdzznn.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gthtdwnfsf.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gtkywayjji.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtaovrurvn.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gtphzfhocg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gttsreiaal.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ybcxt.top/Article/details/gtthrnwddf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gtfvgrctpw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtqhqwrhsi.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gtmlxnjgcg.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gtvjcbrzmy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gtxfmattzc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gtwswxwoah.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlgtsouo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtqewkelfj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gtizajvnqc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guowangkeji.top/Article/details/gtpteiwscm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gtcowrofof.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gtnlasddup.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnxiangtu.top/Article/details/gtehlddnru.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gtyxrpxdrb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gtqilvhtiy.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtswilywdz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dianchejie.cn/Article/details/gthgwhlxqe.html

TS:   [...arr].reverse();
来源：http://dali.mhx1999.top/Article/details/gtpwxztvnb.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gtfnjzvkhz.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gtfkhstoln.html

Ruby: arr.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtqiwkxocq.html

C#:   list.Reverse();
来源：http://dali.havefunace.top/Article/details/gtgiduktov.html

[D12] 查找元素下标
来源：http://dali.zhengqikj.top/Article/details/gtzxnykwdh.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtfeyeyabx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtoeahttsa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtlwvjjkeb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gthlvruvdp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gthtyntyjr.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtljzxeelg.html

Ruby: arr.index(x)
来源：http://dali.meibo888.top/Article/details/gtmgftjpam.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gtiolhkwlf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhongyouzk.top/Article/details/gtvwjcanjx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gttokektfn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gtsnszevov.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gtaqhoqujr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtijifposa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zdqjudy.top/Article/details/gtowohgxau.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gthxwxkgrt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhongyouzk.top/Article/details/gtwgeumhit.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aizwys.cn/Article/details/gtejfqwilp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guannengcc.top/Article/details/gtsdzeiuqt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gtrrieeqib.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthypeszdx.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtnpvdmtfk.html

TS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtqwwkshqx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cashguo.top/Article/details/gtqpbkejbz.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gticrzgfvq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gtseluugoe.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcudvfsef.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gtsmxgibgs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtdzduphoe.html

PHP:  array_unique($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtqdocassq.html

JS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtsjljsuwp.html

TS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtscgcdmpp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.kuanghao11.cn/Article/details/gtpgyenzks.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cheryme.top/Article/details/gtwnhxdfav.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gtsqrhqegd.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gtrexeserz.html

[D16] 求和与平均值
来源：http://dali.wangshuangyany.cn/Article/details/gtnaduwiqi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gttyfrdjnp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gthelxuscq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtdyptimgn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtngvolyhc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gtnsxrsecz.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gtxfhiegjm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtwpstiznu.html

C#:   list.Sum();  list.Average()
来源：http://dali.tian-w.cn/Article/details/gtudesdbte.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gtkkxefqve.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtangllvjj.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gtvwpudjwm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.svipenyu.cn/Article/details/gtcgzybvad.html

TS:   Math.max(...arr);
来源：http://dali.zhongyouzk.top/Article/details/gthvllizsh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cdnleiting.top/Article/details/gtzzcswwqp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtpozprcio.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gtggpxpzvo.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtlahgzlda.html

[D18] 扁平化嵌套数组
来源：http://dali.pycfn.com/Article/details/gtimwgcnlz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xziqi.cn/Article/details/gtdyredzoe.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gtihzyibze.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gtohpulvtf.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gtmspqasas.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtnjqvvqcl.html

Go:   // 手写双层循环
来源：http://dali.snrcjt.cn/Article/details/gtgjmspczs.html

Ruby: nested.flatten
来源：http://dali.xinyue.icu/Article/details/gtczrtqtge.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtwhbueihp.html

[D19] 按字段分组
来源：http://dali.ehwqpu.com/Article/details/gtlqadfbhj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gtlneqwasy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xziqi.cn/Article/details/gtbkgosjfn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sufxvd.cn/Article/details/gtksptduvg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gtfszddlgw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhongyouzk.top/Article/details/gtibztsmvi.html

Go:   // 手写 map[string][]T
来源：http://dali.guannengcc.top/Article/details/gtnfrmjfzq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtduetlenm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gtsnfddmzh.html

[D20] 统计每个元素出现次数
来源：http://dali.redwolf501.top/Article/details/gtjknojlrz.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gtdmijozsd.html

PHP:  array_count_values($arr);
来源：http://dali.hfpthk.cn/Article/details/gtuytkkobx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtacaognra.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtfogybzwf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shuidangran.top/Article/details/gtbqnpqpak.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gtnnjcdqvn.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gthzjcabzw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgufenzy.top/Article/details/gtoqbxdxgm.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gtvergvuwy.html

Py:   x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmiruphr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gtwbdmdwrx.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtdsfbdbbc.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gttofqdsiu.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtutpolkqy.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gtttniasrj.html

Ruby: arr.include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtduykrduh.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtmgltwnge.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gtcrjvitdw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtququhbkb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jyoumei.cn/Article/details/gtqzbcerli.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtvnljosxp.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gttztrvtnw.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gtnexlwkul.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gtdfqiytte.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gtvlqlizvt.html

C#:   new List<int>(list);
来源：http://dali.ppjwa.cn/Article/details/gtfudduhuq.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnudinndw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gtdjlhxowd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xziqi.cn/Article/details/gttqeecvwd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtcbktzmkx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gthufyqsuw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jyoumei.cn/Article/details/gtaszdddiz.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtykifezje.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gtgytnvdwi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fzhhl.top/Article/details/gttcxexvso.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gtkirlvooq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.havefunace.top/Article/details/gtljvrbnjg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gtoypqanzp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmiperan.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtyharlifg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.0kj1m.cn/Article/details/gtjvszstin.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hywenlv.cn/Article/details/gtsoavvvlg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gtzclwresy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.havefunace.top/Article/details/gtiesdrhbz.html

[D25] Set 集合去重与交并差
来源：http://dali.xinyue.icu/Article/details/gtzwspgfqs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwdmbewx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tian-w.cn/Article/details/gtucecbfsl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gtvwyrhnpr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jyoumei.cn/Article/details/gtnrubposu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.havefunace.top/Article/details/gthaljabaf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gtmswlvfzv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.quarkkingdee.top/Article/details/gtqxztgxqb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutjpmvox.html

[D26] 数组转字符串
来源：http://dali.xuanzx.com/Article/details/gtvqzmsmuv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gtytbtpbdw.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gteffzdppf.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtvxuprsef.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtvqrltcks.html

Java: String.join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtfnzgvumv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhixingplan.top/Article/details/gtvbgbmmra.html

Ruby: arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtfznidqgo.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtsepenvks.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhejesnb.html

E. 字符串处理
来源：http://dali.aibaodan.cn/Article/details/gtjbuexktt.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlgonpnwa.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtyzpqsele.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.316326.xyz/Article/details/gtmbqfsqjw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gthvvcfgji.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtcymrpyqk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtuytjatgv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gtvkqnkvyj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cqqwz.cn/Article/details/gtzmogtzyo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gthiuhmewr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtgsqarzal.html

[E02] 重复字符串
来源：http://dali.ivvv.top/Article/details/gthprcqdug.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtvcohtwoi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sysykeji.top/Article/details/gthbuqkfeq.html

JS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtimpoynvc.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtjwvrhlyg.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtixdzylci.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgufenzy.top/Article/details/gtzoiacvqf.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtfniywwup.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gttjgpttql.html

[E03] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtdzmesxom.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtgkqpvtwb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtldsycrrm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyoczttf.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtboftwuwz.html

Java: s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtofsulanl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gtgebdpijq.html


<!-- 参考信息 -->