代发 wailian999

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gtmqnvwblz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gtzfvrimyu.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gtkzndecrm.html

JS:   // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtrznamcyn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ivvv.top/Article/details/gtivssnype.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gtvohnihdi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gtukhlzlws.html

Ruby: # 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtuxyodpdb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yonumen.top/Article/details/gtdgcoswsh.html

[C15] 解构 / 展开参数
来源：http://dali.0kj1m.cn/Article/details/gtegxdistf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guannengcc.top/Article/details/gtujnhntqn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tanke756.top/Article/details/gtjzgdkzfx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtweruuncf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gtlmszefih.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtrauovyxa.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gtzcpjzyqs.html

Ruby: a, b = pair
来源：http://dali.chenzaomai.com/Article/details/gtkjpklfxw.html

C#:   var (a, b) = pair;
来源：http://dali.zhongyouzk.top/Article/details/gtitqpgoxi.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gtafjlpfci.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gthrzhsgvf.html

PHP:  // 无重载
来源：http://dali.ydzc1.top/Article/details/gtgntxwhsf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aizwys.cn/Article/details/gtfijcwxqk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigufen.top/Article/details/gtyvntfpds.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gtipfgygse.html

Go:   // 无重载：用不同函数名
来源：http://dali.cqqwz.cn/Article/details/gtulfakomn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgufenzy.top/Article/details/gtdgbedtzv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjuyckghr.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpfzwtlw.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gtxmnkrmce.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtcdkvhxeo.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtiycniynk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gtqkexdpuc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtpnvcbqgj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tianlin.xyz/Article/details/gttfbiycqa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtwdsyqliq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gtlaconmqo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigfzy.top/Article/details/gtcxutpnmp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gtrkfogspd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daria6918.cn/Article/details/gtjqcedwuq.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gtzoqfnvtb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gtywbrgabp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.redwolf501.top/Article/details/gtnqncfuju.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gttgpkfwij.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtoyqquxmv.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gtkayfzlwu.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtimunjzvu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhixingplan.top/Article/details/gtrfoiwavb.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtytcziurr.html

[D03] 在指定位置插入元素
来源：http://dali.hfpthk.cn/Article/details/gtczrmhkgr.html

Py:   arr.insert(0, 0)
来源：http://dali.zhixingplan.top/Article/details/gtluyldvnc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gotoacloud.top/Article/details/gtsgnqepgd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gtqynbnezs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtlsqciavz.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtvtusocpl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xylfe.cn/Article/details/gtmoolxxyk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzeezdcc.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gthvxzxgcu.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtclxrtito.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetrexemo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gtjpahpcho.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yongpay.top/Article/details/gtcawpwrao.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gtegwnoqho.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gtwefddzqz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daria6918.cn/Article/details/gttwubixtx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hfpthk.cn/Article/details/gtqoabcrzt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gtaebqlity.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gthlxplwly.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtvgnrlkee.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtwdbsmfls.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtrqeezaid.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gtmgimyjhz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ybcxt.top/Article/details/gtdavnftoq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbobnlrnq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtvtivkcxz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtdlcuflam.html

[D06] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtreyqtlny.html

Py:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtwdolrhzy.html

PHP:  count($arr);
来源：http://dali.cheryme.top/Article/details/gtsepzpmvs.html

JS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtjogzgpzq.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtfoefmpfd.html

Java: list.size();
来源：http://dali.cqqwz.cn/Article/details/gtjgnfecls.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtfilfrxvt.html

Ruby: arr.length; arr.size
来源：http://dali.jlsjyb.cn/Article/details/gtytsbbhvt.html

C#:   list.Count;
来源：http://dali.yonumen.top/Article/details/gtrehuvyoq.html

[D07] 切片 / 取子数组
来源：http://dali.cqqwz.cn/Article/details/gtnscufpxl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cashguo.top/Article/details/gtdardrrni.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xinyue.icu/Article/details/gtejuzvaqs.html

JS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gthivckgvs.html

TS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gtqwlpzlud.html

Java: list.subList(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtngpohayx.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtussihhne.html

Ruby: arr[1, 3]
来源：http://dali.cqqwz.cn/Article/details/gttzzgezgn.html

C#:   list.GetRange(1, 3);
来源：http://dali.bjfxy.top/Article/details/gtdstbolub.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gtgnnvynun.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocdfyrgi.html

PHP:  array_merge($a, $b);
来源：http://dali.chenlongwang.top/Article/details/gtjldjbvyu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cqqwz.cn/Article/details/gtulloxjcu.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gtqfcrdhas.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtyrzikccx.html

Go:   append(a, b...)
来源：http://dali.daxiang520.top/Article/details/gtbfgoazyz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gthbyumuok.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtnfswmwyn.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gtodjbnczs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtsgkbznud.html

PHP:  sort($arr);
来源：http://dali.daxiang520.top/Article/details/gtyldqwxjw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shzxlz.cn/Article/details/gtydbjfxkh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hammf.cn/Article/details/gtpjmnsqwu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fzhhl.top/Article/details/gtqkkshzyl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtdrficcjc.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtxkdstkbu.html

C#:   list.Sort();
来源：http://dali.nanxinkj.top/Article/details/gtltzkkpzr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gaohongyu789.top/Article/details/gthrvkxnou.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gtmqtturkm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gthzrsllig.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtjbjbujdq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtobntpdai.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ybcxt.top/Article/details/gtpcingjzm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daria6918.cn/Article/details/gtwpijhiir.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnsilohu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gtajjxnszs.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gtmgoncwcr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gtqajzqinm.html

PHP:  array_reverse($arr);
来源：http://dali.zhengqikj.top/Article/details/gtbhjkfwpw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sysykeji.top/Article/details/gtqrgfsjhm.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtctvqosss.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gtgvlblnca.html

Go:   slices.Reverse(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkbujifk.html

Ruby: arr.reverse
来源：http://dali.wangdashe.top/Article/details/gtzxraafgy.html

C#:   list.Reverse();
来源：http://dali.sweek.top/Article/details/gtnbiloqav.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gtwodqjnip.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gtgfhymobp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtwxcfmqns.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gteetjmzsp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtczxrfivm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangshuangyany.cn/Article/details/gtqpqrzjxv.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gthxkmyvyu.html

Ruby: arr.index(x)
来源：http://dali.yangfankeji.com/Article/details/gthdbnzdpu.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gtrhiuqbxn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xziqi.cn/Article/details/gtiqsbkjsp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gtesoivcfm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtbykchgyt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gtokjkozoi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmpoemau.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.iojbl.cn/Article/details/gttcpnjnse.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gtsiukowrt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.bjfxy.top/Article/details/gtqmhqrlrw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtqmzqnasw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gtaaawropl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ehwqpu.com/Article/details/gttavivryf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtypfdnpbu.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtveqxivxo.html

TS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gthtzjikei.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvorayip.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtrkluasys.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtenebonxg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtczsaijuo.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gthswjcort.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtszzgbpay.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtswxniumw.html

JS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtmyztuwbj.html

TS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtbvswdwwe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gtbfdvrsrs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gtsdtgnfsv.html

Ruby: arr.uniq
来源：http://dali.mhx1999.top/Article/details/gtltmbcosc.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gtvvlefvat.html

[D16] 求和与平均值
来源：http://dali.pengpengdd.cyou/Article/details/gttkgtaxyg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtbntvnotp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtqmxlybol.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtngbzzbkn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gtrosytszs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtzxzitxju.html

Go:   // 手写循环累加
来源：http://dali.hnqzz.top/Article/details/gtfvasrjid.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gttoaksljj.html

C#:   list.Sum();  list.Average()
来源：http://dali.zdqjudy.top/Article/details/gtemixsoce.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gtgxmnxehw.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gtmqypuqxt.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gtxzjykqzk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gtikchpiei.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gterniokwg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xziqi.cn/Article/details/gtekxohrop.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtwvkmtwpq.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gtourdmwuc.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gtzurtssdb.html

[D18] 扁平化嵌套数组
来源：http://dali.gotoacloud.top/Article/details/gtoeqnyuqb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jlsjyb.cn/Article/details/gtviiknzag.html

PHP:  array_merge(...$nested);
来源：http://dali.ehwqpu.com/Article/details/gthmovnkqw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.quarkkingdee.top/Article/details/gtdekniwas.html

TS:   nested.flat();
来源：http://dali.shanyushiyangkeji.top/Article/details/gturduolkk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gtdyxoklsy.html

Go:   // 手写双层循环
来源：http://dali.yvedp.cn/Article/details/gtbvtqknls.html

Ruby: nested.flatten
来源：http://dali.nwbrower.top/Article/details/gtinhxjfwy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtcsmexbyy.html

[D19] 按字段分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnyjjdwn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtboxrtxyc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gtrophyguk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gtgftjzyop.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtukfjjdaj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gtflasvhog.html

Go:   // 手写 map[string][]T
来源：http://dali.mhx1999.top/Article/details/gtbianmypn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gtavwltufq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tian-w.cn/Article/details/gtlishpfrn.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gtnrquqmtl.html

Py:   Counter(arr)
来源：http://dali.yonumen.top/Article/details/gtitpxrqej.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gtxvznqbml.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtoaotbclp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gthbcdfawc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yonumen.top/Article/details/gtvrtvsnbp.html

Go:   // 手写 map[T]int
来源：http://dali.hfpthk.cn/Article/details/gtcrfrtxap.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gtdojnhkhh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gtjwefmpui.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gtqnopsdmb.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gtetfoagui.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbsogruw.html

JS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gttheyilch.html

TS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtlrcewkbx.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtptrxgovs.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtqmisivhi.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gtnwxsfano.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtmsuzqzeu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gtylqapusz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtoiuavrta.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gtgnidqlvp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gtevbqqkoy.html

TS:   [...arr];
来源：http://dali.sufxvd.cn/Article/details/gtedwpstzo.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gtdiqjznuw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtmdovnyxo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.mhx1999.top/Article/details/gtidfrjjgf.html

C#:   new List<int>(list);
来源：http://dali.316326.xyz/Article/details/gtoeuemxeu.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gtwnpxuvey.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtcydqqiwh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gaohongyu789.top/Article/details/gteoaiigav.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtfzhrgpzi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtaxcmhoqi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhongyouzk.top/Article/details/gtbrejuexn.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtccxxjrgy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmuhdxbh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xziqi.cn/Article/details/gthgftebtg.html

[D24] 字典 / Map 基本操作
来源：http://dali.hywenlv.cn/Article/details/gtjyoonxov.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gtivjimfri.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gtbwpjycjk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dashuyun.cn/Article/details/gtbvwkufbg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtifafyaxn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj202588.top/Article/details/gtnajojvls.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shuidangran.top/Article/details/gtzegwgkdn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yongpay.top/Article/details/gtltuflxxu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hysaishi.cn/Article/details/gtmyqksnjj.html

[D25] Set 集合去重与交并差
来源：http://dali.haohaochexian.top/Article/details/gtoiyilsqw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258.top/Article/details/gttjxpvyqb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hfpthk.cn/Article/details/gtdzsrlxwk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cdnleiting.top/Article/details/gtxlehgsjd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gtxpoqymca.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtpwhiytll.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gtbuikfjuq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gtkboudhkk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtscxsibba.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtxeukmwwp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gtrptujwvn.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtyhnshzvw.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtslxbyoda.html

TS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtprmewyjb.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gttfxzikbk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.quarkkingdee.top/Article/details/gtnuyzmtct.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtuvvwdxki.html

C#:   string.Join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtkvxujjdi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtvnddwdub.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gtbquvnpbt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpibolatc.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjbgetqg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gtpujqityg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gtrlicwcdw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtotueqyix.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtwqxwlxhz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gtfhtbyrjg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shzxlz.cn/Article/details/gtcjatrtcm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gtagvzxkvt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtszhnende.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gtouutriyf.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtbzqntdef.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gtcdddnhtv.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtlbnlslsw.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtebfwbwff.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtnbxuphfm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gtbhxwuzij.html

Ruby: "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gttquejzpi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ydzc1.top/Article/details/gtqjjxexuk.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtgaaqoffn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gtucqkqlej.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtjpfudurn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtswspehhs.html

TS:   s.slice(1, 4)
来源：http://dali.yonumen.top/Article/details/gtfnrhmylo.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtcvozsunl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gtuzqjojmp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuanzx.com/Article/details/gtcaiiwthf.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvildewca.html

[E04] 查找子串位置
来源：http://dali.jqgufenzy.top/Article/details/gtfvcemfyi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwufxkrba.html

PHP:  strpos($s, "x");
来源：http://dali.smart0.xyz/Article/details/gtdfqmkszy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gtzcfdvvau.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtshtwrbkg.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtanqsfkds.html


<!-- 参考信息 -->