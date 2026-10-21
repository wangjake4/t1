代发 wailian999

[C14] 泛型函数
来源：http://dali.yonumen.top/Article/details/gtfelfuwow.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.quarkkingdee.top/Article/details/gtwjyoplqf.html

PHP:  // 无泛型
来源：http://dali.wangdashe.top/Article/details/gtzjtdqfvt.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtezmflxlc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gtumixbjiq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtztgikzun.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbddwyvys.html

Ruby: # 无泛型
来源：http://dali.cashguo.top/Article/details/gtwldcaicb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fzhhl.top/Article/details/gtazqnvujt.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gtgnxfhrgi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gtxxrexfvi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.9152youxi.cn/Article/details/gtnclxqwcb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtcurjqhmp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hfpthk.cn/Article/details/gtrgsvlapv.html

Java: // 无解构
来源：http://dali.c1oappe.top/Article/details/gtidsafpqp.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gtskyqqulk.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gtkdbvuyls.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gtoxspsrla.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gtawzyikzp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gtqktzcmvj.html

PHP:  // 无重载
来源：http://dali.pengpengdd.cyou/Article/details/gtdbzociuy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgfzy.top/Article/details/gtpnxnwhzi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gtloxlrqxu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxuanxn.top/Article/details/gtetwmylzn.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhtartej.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jiagoushi.top/Article/details/gtkmhvfudn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtesuoredq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtyyilmfpc.html

D. 数组 / 列表 / 集合
来源：http://dali.yvedp.cn/Article/details/gtzwkbhjro.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkcewaegj.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtrtkbhsju.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenjidiqi.icu/Article/details/gtygkkipvi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtdyunvthl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.redwolf501.top/Article/details/gtslnewnwr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gtwxgejvlc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenjidiqi.icu/Article/details/gtbuhibwdt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.andypj.xyz/Article/details/gthsrxrgnc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jianghu66.top/Article/details/gtduuuivsr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daxiang520.top/Article/details/gtagbabasd.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gtdefuerst.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnqzz.top/Article/details/gtfotwvmzf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtnlmtclrl.html

JS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtjmqwutoy.html

TS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gtxcediasv.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gtcauezjdx.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigufen.top/Article/details/gtzahzwknv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.svipenyu.cn/Article/details/gtaflcekuv.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gtmixmkbhe.html

[D03] 在指定位置插入元素
来源：http://dali.yuanzhike.top/Article/details/gtgsxkybda.html

Py:   arr.insert(0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtmgeotsdr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxgbaaui.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.redwolf501.top/Article/details/gtjzntfadm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gtvxyfsdxr.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtqprwiujb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gtednoqszv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aizwys.cn/Article/details/gtwklpnzsx.html

C#:   list.Insert(0, 0);
来源：http://dali.tanke756.top/Article/details/gtfzhhceya.html

[D04] 删除元素
来源：http://dali.tianlin.xyz/Article/details/gtgrbyapnq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hfpthk.cn/Article/details/gtlfvifhrr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtvoykbtnh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dashuyun.cn/Article/details/gttlgnfffm.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gtksbbshar.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gtfgpouwpo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gtipaxevft.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gthdxihsch.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gtuxmxuvwg.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gthznlxhbz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtvvxxggnf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkzqebgb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtwqjhlhur.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gtzuyelduv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gtrkohveuk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtxboxvajn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtbhdlfbfh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gthjrehajv.html

[D06] 数组长度
来源：http://dali.tanke756.top/Article/details/gtelaagqhx.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gttxarxemt.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtvkqnwslv.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtcphwpffr.html

TS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtfrnychlg.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gthswvcgfq.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtzrodsgoe.html

Ruby: arr.length; arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztvtdcex.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gthxeltxju.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gtsgauyipy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj202588.top/Article/details/gtroxtpsta.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gtxxcwuqav.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtqnaoozim.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtmhsgdmcr.html

Java: list.subList(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtzwfefxwn.html

Go:   arr[1:4]
来源：http://dali.jinqigufen.top/Article/details/gtcyulubvp.html

Ruby: arr[1, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtmbtifvji.html

C#:   list.GetRange(1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtbggqlqje.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gtphuypjrp.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gtctxgcjdc.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gtptucvojc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gtvbvtatmp.html

TS:   [...a, ...b];
来源：http://dali.jqgufenzy.top/Article/details/gttryqcvnw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtoaenguqo.html

Go:   append(a, b...)
来源：http://dali.cheryme.top/Article/details/gtwqycawnq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtosslprhp.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gtfkpkncip.html

[D09] 排序（升序）
来源：http://dali.hammf.cn/Article/details/gtqqzuowke.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtrrntepgd.html

PHP:  sort($arr);
来源：http://dali.dashuyun.cn/Article/details/gtgjigkmqv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gtdqpmswzo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gtkegxwqvq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tianlin.xyz/Article/details/gtvloeelis.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqygmhlkp.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzozdbhdz.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gtiqhdbohj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcyxzdiq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gtfkvljbsd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gtvbxuztwa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gtcjnsrnhy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gtdoqnhgcv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrgvsujc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gtuchptymn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ydzc1.top/Article/details/gtpwdkadgd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tian-w.cn/Article/details/gtldmocvra.html

[D11] 反转数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhilqylv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shzxlz.cn/Article/details/gtdxmbsvcw.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtclxaxzhr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gtdixyfssv.html

TS:   [...arr].reverse();
来源：http://dali.zhixingplan.top/Article/details/gtyceoquow.html

Java: Collections.reverse(list);
来源：http://dali.jiagoushi.top/Article/details/gtaaxcqaba.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gtzmwegylh.html

Ruby: arr.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtyfqgylsn.html

C#:   list.Reverse();
来源：http://dali.yuxming.cn/Article/details/gtypmrvanr.html

[D12] 查找元素下标
来源：http://dali.yj202588.top/Article/details/gtxsdvermt.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gtzktdfres.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yvedp.cn/Article/details/gtppfwqdlc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtteyjmbrf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gtxnmylsaa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuetiantiany.cn/Article/details/gtnilfwlns.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtxqmzeokf.html

Ruby: arr.index(x)
来源：http://dali.zhengqikj.top/Article/details/gtinioqeil.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gtxysxylya.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gtdsgvtakq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtpiqaqawt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gtkqsfmjhd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtuuidduve.html

TS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtfbmvetpr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gtugjbpfhf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zycfv.cn/Article/details/gtqfzbwoge.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigufen.top/Article/details/gtjkbmpznj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gtvstdtkjc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aizwys.cn/Article/details/gtvwupcird.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hammf.cn/Article/details/gtftfudklp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtrodqobyd.html

JS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gtetswerrf.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtahhnxbxp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtbsbryzzs.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtsjoefjjk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtbgchnvlr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtvwvvsxul.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gtjijmulak.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtvyeegtow.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gtvwxjejxf.html

JS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtwtqowsze.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtxsbgmtmp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvyfseek.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.bjfxy.top/Article/details/gtsqqivvrn.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gtsvjftkad.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gtgimbtnpf.html

[D16] 求和与平均值
来源：http://dali.pengpengdd.cyou/Article/details/gtpjqlzqdu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gthlkewlmy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yvedp.cn/Article/details/gtarotkwen.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtcbvdwulq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtpkivdupj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gtytbojyvo.html

Go:   // 手写循环累加
来源：http://dali.sysykeji.top/Article/details/gtokpjpcqo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tanke756.top/Article/details/gtxjefshzd.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gtoduycdib.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gtynhgyeru.html

Py:   max(arr);  min(arr)
来源：http://dali.gzhubu.top/Article/details/gtrvadayeo.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtnhzfqgqm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gtemkmugvn.html

TS:   Math.max(...arr);
来源：http://dali.aizwys.cn/Article/details/gtibqkhfzo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gtgjkdlibm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gtnqlmgaxd.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gtbqwdhmms.html

C#:   list.Max();  list.Min()
来源：http://dali.316326.xyz/Article/details/gtkzxaoikq.html

[D18] 扁平化嵌套数组
来源：http://dali.ehwqpu.com/Article/details/gtiumydlpe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigufen.top/Article/details/gtquujzyze.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gttzhdpvdc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.vqdsnc.cn/Article/details/gtcrkkobmk.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gtffattwpf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtqmdiphdd.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gtbjsoeyyx.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gtdftyupxw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gtpdafeanf.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gtlhgsxzjc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gtwgnohruo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtjklqfqqx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenlongwang.top/Article/details/gtsyspxivr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgokvqdi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gtokogielg.html

Go:   // 手写 map[string][]T
来源：http://dali.kuanghao11.cn/Article/details/gtdqhshibp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gtzwfwafdy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gteamnofwc.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gtsxjkiucl.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gtzysrlrxd.html

PHP:  array_count_values($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscfqlyaa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtigplthxr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtowyswqeh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258.top/Article/details/gtbfivewab.html

Go:   // 手写 map[T]int
来源：http://dali.xziqi.cn/Article/details/gtylrpwfzp.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gticehgwjf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gtkxuffguu.html

[D21] 判断是否包含某元素
来源：http://dali.cheryme.top/Article/details/gtjeuhyxfk.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtymxsexrx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfvlfofl.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtzqhgiczc.html

TS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtatjkhgzm.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gtgbakncxc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtmgbapffr.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gtydawwgqr.html

C#:   list.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtjhzpxwss.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gttsrmmuie.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gteoiuvawm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gtjidzmnfj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gtedklkmdz.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gtbfvzeejh.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gtorbmwygs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gtvtghejwr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shangyingyoupin.top/Article/details/gtybgangcb.html

C#:   new List<int>(list);
来源：http://dali.c1oappe.top/Article/details/gtqvahablf.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gtkemxrppu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gtonvrviig.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtwhfyjmlz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtmbvweqnx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtvjacwidt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gtjrsrjszd.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtsakxdist.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gtxoquiaux.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gtnaigjdzw.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gtmergtakl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gtijuoeqjb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jyoumei.cn/Article/details/gtnhofoyec.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gtyzqmumze.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtjaytatbi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gogol.net.cn/Article/details/gtkwzhugoh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gtpwyegcpg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xziqi.cn/Article/details/gtnadboota.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gtjafdixgy.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258888.top/Article/details/gtpqxrsqww.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtqiqgrzno.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.316326.xyz/Article/details/gtemaibgmo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtddupiefm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gtrrfhowyn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gtqixkucix.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gtbzbxznri.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gtrjsmxjlt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gtaltfrpfv.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gttmeiavlc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtpqlsxmvl.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtywgfkvrp.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtwewgfnpk.html

TS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtduxscgee.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtsrfqagyf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhixingplan.top/Article/details/gtanwltziz.html

Ruby: arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtrpxknbrx.html

C#:   string.Join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtjcymhgqk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmlpwczej.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gtgvgeglzo.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtcvrryksj.html

[E01] 拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtffasurrt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gtjtmudntd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gtqpqapibl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtwtthopkp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gtxgavjbey.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.havefunace.top/Article/details/gtjfsskbwb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hywenlv.cn/Article/details/gtobljlzpw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hammf.cn/Article/details/gtzxixuidf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtatdasaxa.html

[E02] 重复字符串
来源：http://dali.zhongyouzk.top/Article/details/gttbvtgqfv.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtkvaavrkx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gtnvufoiqq.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrqwpvzk.html

TS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtodaslxpp.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxtqpsha.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazsrekbk.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtzvjuomgc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gthyubiyyn.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtxaveohib.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gtpnkaiiza.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtuuvcrpnj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtugkheryw.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258888.top/Article/details/gttisigbse.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtqficqamx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtqsxdqiuj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.snrcjt.cn/Article/details/gtwkrehyny.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gtzffeeiub.html

[E04] 查找子串位置
来源：http://dali.pengpengdd.cyou/Article/details/gtegfqknkx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtcpriyjrc.html

PHP:  strpos($s, "x");
来源：http://dali.cheryme.top/Article/details/gtcxmquttw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtbroudful.html

TS:   s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtlsssxtkr.html

Java: s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtjvyqejgs.html


<!-- 参考信息 -->