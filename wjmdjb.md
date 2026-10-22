代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gtrwmjvxxe.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gtipfzfhfo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtuenrvxky.html

[C13] 类型声明 / 类型注解
来源：http://dali.iojbl.cn/Article/details/gtkseudvdp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnqzz.top/Article/details/gtqqpzbipw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtewiepetm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yvedp.cn/Article/details/gtzhtfczpi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtookpopbw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtymrotjpq.html

Go:   func add(a, b int) int
来源：http://dali.meibo888.top/Article/details/gtbodkmrue.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxobtoveh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigufen.top/Article/details/gtiuspyfdx.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gtdqixvuwp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nwbrower.top/Article/details/gtxuganntk.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtqcibmhkq.html

JS:   // 无泛型
来源：http://dali.yj20258.top/Article/details/gtjawwjlbi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pycfn.com/Article/details/gtbcntkspn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtfyatopje.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258888.top/Article/details/gtcmkdkrqm.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtccnupvum.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gtynhcwray.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gtnhfqzcxs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gtshuguuwn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jyoumei.cn/Article/details/gtszzqjbgo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtqbeuyldz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gtxbcvlygu.html

Java: // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gtopobbrrh.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtubxzrjjf.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gtdwgdvhna.html

C#:   var (a, b) = pair;
来源：http://dali.hysaishi.cn/Article/details/gtswhxndze.html

[C16] 函数 / 方法重载
来源：http://dali.jyoumei.cn/Article/details/gtolytvmvu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gtdlndgcey.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gtcvmhwsch.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtpyfzlrmc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigfzy.top/Article/details/gtcionvwnu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hfpthk.cn/Article/details/gtpiylkjcn.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gtlkodjojv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhongyouzk.top/Article/details/gtautsutme.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jianghu66.top/Article/details/gtaqrlihqk.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtkeiboxiu.html

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gtzqdvaktk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfrabmnsb.html

[D01] 创建数组 / 列表
来源：http://dali.fzhhl.top/Article/details/gtqrpgyhuh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gtkldtjufj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtebwmvvwe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gtffenkhsd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gtuijfkxub.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigufen.top/Article/details/gtuaobnodx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gotoacloud.top/Article/details/gtbqmketiv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gthodbachd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ydzc1.top/Article/details/gtwqmamoie.html

[D02] 追加元素到末尾
来源：http://dali.hnxiangtu.top/Article/details/gtqdrqtndm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yonumen.top/Article/details/gttgvzlfmt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gtyptpwjqq.html

JS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtysyavxso.html

TS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtxmmjeyss.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gtsqbxiyaq.html

Go:   arr = append(arr, 4)
来源：http://dali.hfpthk.cn/Article/details/gtkzpozwvw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hfpthk.cn/Article/details/gtsxyespbx.html

C#:   list.Add(4);
来源：http://dali.redwolf501.top/Article/details/gtxytvdldl.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gtskkshbyu.html

Py:   arr.insert(0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoquvaioy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gtuldqzkpj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gtxyssrzop.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtxiklqwoz.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtrhzujvvb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gtxgipsihi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gtuzkrukba.html

C#:   list.Insert(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtuaysalhh.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtxshcyhyc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtkqzzoavg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangdashe.top/Article/details/gtlyqwjxle.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.0kj1m.cn/Article/details/gtkfxozzft.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gtiauthxei.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xinyue.icu/Article/details/gtqsqksgeq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yanxiufei.cn/Article/details/gtthhwarrt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258.top/Article/details/gtqwyzgjmg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jyoumei.cn/Article/details/gtomlkiwfp.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gthjdopvng.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtxoxfvxvz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybbppeip.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtptwgcfia.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gtsxksbxql.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nwbrower.top/Article/details/gtxpejyyjh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gteoffcwzk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtlvqhmnhv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtvwjbyoby.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtcnkwwtju.html

Py:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtwlefztro.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtrhvvsjga.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtickfhxjx.html

TS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtbbwcccmn.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gtucuulehf.html

Go:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtktippogm.html

Ruby: arr.length; arr.size
来源：http://dali.birdmap.top/Article/details/gtmeqcankj.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gtnyjycbvn.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gtsvngumnk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhiwuduotai.top/Article/details/gtjxyjfqsn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gtyluitcak.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtpdlztmmr.html

TS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtepxwkmsr.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtxpejdajg.html

Go:   arr[1:4]
来源：http://dali.fengsongda.top/Article/details/gtnzvxtejk.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gtmybdlezk.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gtbnusvjba.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gtrkdrubwq.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gtvsftckdo.html

PHP:  array_merge($a, $b);
来源：http://dali.bjfxy.top/Article/details/gtlbrnjcxq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gtgzakfbqu.html

TS:   [...a, ...b];
来源：http://dali.smart0.xyz/Article/details/gtleodyumc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtbsugnfqa.html

Go:   append(a, b...)
来源：http://dali.xylfe.cn/Article/details/gtetemzhio.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hysaishi.cn/Article/details/gtnstzkahp.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtdssbxlys.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gtenixcxga.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuqutkgv.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gtxrfhwjat.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gtdmjhelpk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ehwqpu.com/Article/details/gtodfadgwo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnxiangtu.top/Article/details/gtijuqucsr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtbiyohkua.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtmxcckiph.html

C#:   list.Sort();
来源：http://dali.9152youxi.cn/Article/details/gtrfqhlnyk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangshuangyany.cn/Article/details/gttkdzvapw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnfhuwqn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gtqwxgalvg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtzfliniax.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtmjdaioes.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvuwvoes.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.9152youxi.cn/Article/details/gtuyavyihl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guannengcc.top/Article/details/gtomsnioxi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.316326.xyz/Article/details/gtnifmlyqg.html

[D11] 反转数组
来源：http://dali.ybcxt.top/Article/details/gtxmwljizp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gtlpwqflzb.html

PHP:  array_reverse($arr);
来源：http://dali.fengsongda.top/Article/details/gtsgzlwvns.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gtxtmxwmbh.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gtbmfceedy.html

Java: Collections.reverse(list);
来源：http://dali.zhongyouzk.top/Article/details/gtmoovdncd.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gtqrprypne.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gtwbuctvxk.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gtcpoxsfvj.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryqazwpi.html

Py:   arr.index(x);  x in arr
来源：http://dali.zdqjudy.top/Article/details/gtpdhogsta.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtaargeuia.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gtweapgrgp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gtboakotsj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.0kj1m.cn/Article/details/gtifijxcbd.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtxtdhinct.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gtnbnsehle.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gthgiatppu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gtehcyfbhx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtoscwksjg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gtlkhigoxk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtznqqjgym.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gteseggrcj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtzfpxdfwz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gtwbqyusie.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangdashe.top/Article/details/gtumgvwbyx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtbfewhdvr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.meibo888.top/Article/details/gtuvicwnzo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gttoxoeeiw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtkrsaljyv.html

JS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gtybymcruu.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gtqfnnkwhv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gthhnwbwpl.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtupezdqkd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gthwmfxzcg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nwbrower.top/Article/details/gtgekqnkhi.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gtiggujtzc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtadotuicf.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gtzetxkwrj.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtcjdyclsc.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtplwrffbn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhengqikj.top/Article/details/gtfzkajicf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.bjfxy.top/Article/details/gtjvytscca.html

Ruby: arr.uniq
来源：http://dali.xziqi.cn/Article/details/gthneptfqj.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gtdlxechor.html

[D16] 求和与平均值
来源：http://dali.hnqzz.top/Article/details/gtluzvhsqy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtlifydsgk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtovrgochl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtbhwtsjyq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtqccptsdn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yueranfly.top/Article/details/gthrmlxrwd.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gttndttweh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxinkj.top/Article/details/gtukxhgfbx.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gtearxerzp.html

[D17] 最大值与最小值
来源：http://dali.ppjwa.cn/Article/details/gtmsnooobj.html

Py:   max(arr);  min(arr)
来源：http://dali.yongpay.top/Article/details/gtuuegvxfk.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangdashe.top/Article/details/gtxaqokjxc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenjidiqi.icu/Article/details/gthdxmyecm.html

TS:   Math.max(...arr);
来源：http://dali.haohaochexian.top/Article/details/gtljdboxgl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gttvzuxkgj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtovbhebix.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gtmcfyamrn.html

C#:   list.Max();  list.Min()
来源：http://dali.tanke756.top/Article/details/gtqqmpvwcl.html

[D18] 扁平化嵌套数组
来源：http://dali.birdmap.top/Article/details/gturfmcbcu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gtfwfgxnhu.html

PHP:  array_merge(...$nested);
来源：http://dali.zycfv.cn/Article/details/gthbbpgljr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gtekxzruuc.html

TS:   nested.flat();
来源：http://dali.snrcjt.cn/Article/details/gtijlmwrbh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpofegtj.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gtojkxxhgc.html

Ruby: nested.flatten
来源：http://dali.ivvv.top/Article/details/gtpzadunde.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtytovolva.html

[D19] 按字段分组
来源：http://dali.gzhubu.top/Article/details/gtoyaysygc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtlfxdbqba.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.smart0.xyz/Article/details/gtajzlhkjx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlyssplp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gtwbunknqw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gtfjdfulpi.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gtalxvksjj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gttfnhaozd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cheryme.top/Article/details/gtjbdxyzut.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gtmhtcusry.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gtouyhqbpw.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gtxxkujkqp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtwinexbxx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtpglconlq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gttnnxevpk.html

Go:   // 手写 map[T]int
来源：http://dali.zhiwuduotai.top/Article/details/gtvmroevyf.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gtldkwwqdw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj202588.top/Article/details/gtpvyqbfgw.html

[D21] 判断是否包含某元素
来源：http://dali.jianghu66.top/Article/details/gtgwidvkzu.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gtlrlpymui.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzuodghn.html

JS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gttrphmdqd.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gtqfouqcxd.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gtbbdeswnr.html

Go:   slices.Contains(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtifvbmwyh.html

Ruby: arr.include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtugiwxqrq.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtaltaejkz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yangfankeji.com/Article/details/gtqnbmbqck.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuanzhike.top/Article/details/gtrxbpxjaz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gtofhfxtlh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gtmkezjaij.html

TS:   [...arr];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfertbwa.html

Java: new ArrayList<>(list);
来源：http://dali.yuxming.cn/Article/details/gtmcbgpxak.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.snrcjt.cn/Article/details/gtirhxbttp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gtxzbizrqx.html

C#:   new List<int>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtjeuefjky.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gtgvvstovo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtinnuehrg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xziqi.cn/Article/details/gtoqhvtphx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtiuclzgrz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtvlarzeoh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cdnleiting.top/Article/details/gtipyqhyfr.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtnvwmymyw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gtkbsgbudu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fengsongda.top/Article/details/gtevaikohb.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gtvisbkeow.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gtbqjsmidp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gtonrdefae.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gtjjcoxeww.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtdftluutf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibhobjbs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guannengcc.top/Article/details/gtjabcshft.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gaohongyu789.top/Article/details/gtdklcmwfr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dianchejie.cn/Article/details/gttwmzfypj.html

[D25] Set 集合去重与交并差
来源：http://dali.meibo888.top/Article/details/gtzjehhice.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgufenzy.top/Article/details/gtaxjlwxmi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gtcyuiedci.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gtopstfuae.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.quarkkingdee.top/Article/details/gtkrjycepw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gtxmyrvslc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ydzc1.top/Article/details/gtfpxjbovf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gtebsonaae.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj202588.top/Article/details/gttjewpsws.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gtoyswqpjh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gtlezhxlei.html

PHP:  implode(", ", $arr);
来源：http://dali.andypj.xyz/Article/details/gtvvpepxsm.html

JS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtbzfpiiyh.html

TS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtiehajevx.html

Java: String.join(", ", list)
来源：http://dali.yj20258.top/Article/details/gtpedgplvt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gtglxijmot.html

Ruby: arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtelzaxtsc.html

C#:   string.Join(", ", list)
来源：http://dali.tanke756.top/Article/details/gttvzeyizc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtyiyumyfg.html

E. 字符串处理
来源：http://dali.cashguo.top/Article/details/gtekcyqhpp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsolqwfwo.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtltjuckra.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258888.top/Article/details/gtezqravgj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pycfn.com/Article/details/gtlipzzjpk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtpixrgdum.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtnstnkrqe.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gtrywfwwmg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gtlvjyzppe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtjamotrft.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtdawkzddi.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gtdzdvnzxh.html

Py:   "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtvdfsceec.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gtyvdlesep.html

JS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtgmchazai.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtrmyavgay.html

Java: "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtcgszrumr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gtxswtijvf.html

Ruby: "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtjhiuqyps.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtoaluibzl.html

[E03] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtnzqjwbpc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gtrxqeoixn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsrorwpt.html


<!-- 参考信息 -->