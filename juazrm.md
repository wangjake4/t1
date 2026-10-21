代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gtpmhhasin.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gtkamkkiuk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.smart0.xyz/Article/details/gtegydhbwl.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gtflwxmjeo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gtiroreujh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrglymdhe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbskyeqw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtjqqwyqzf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtvmnsirew.html

Go:   func add(a, b int) int
来源：http://dali.dianchejie.cn/Article/details/gtanrqavqa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fengsongda.top/Article/details/gtewwqhven.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenzaomai.com/Article/details/gtvzbprtws.html

[C14] 泛型函数
来源：http://dali.hysaishi.cn/Article/details/gtnhzluxth.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gtxkhzeqli.html

PHP:  // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtaxebwnno.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtueujxczx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gtzjkrbucb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gthkgtjnds.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gtrttmvkvw.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gtnkajxlwf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gtutonvpyd.html

[C15] 解构 / 展开参数
来源：http://dali.gzhubu.top/Article/details/gtebhyoqsr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gtcgvojcxp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuxming.cn/Article/details/gtiljcapnb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtibisviuz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gttyybbklt.html

Java: // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtpiftfpcy.html

Go:   // 无解构
来源：http://dali.tanke756.top/Article/details/gtllcrlkof.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gtinyyvxhs.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gtxfrycdjt.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpcnjtyc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gtztsgcpfk.html

PHP:  // 无重载
来源：http://dali.dashuyun.cn/Article/details/gtyclehgez.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gtvkwdqovg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.0kj1m.cn/Article/details/gtzorninmy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gtehzeutyk.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gtzmbaolmo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gogol.net.cn/Article/details/gtkqpoqgwn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.0kj1m.cn/Article/details/gtnnhlksck.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtyfvsvdsx.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gtqxhckuqw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtyunmjzsb.html

[D01] 创建数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxnefwuq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtgdzhiqwh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yongpay.top/Article/details/gtoygaobzq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtmztuevdf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gtzyfxyzjo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.smart0.xyz/Article/details/gttpnzsfeq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.quarkkingdee.top/Article/details/gtfrqibrzo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gthgtaaaus.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gtuercckkm.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gtzwnyhair.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.feifeiyinyue.top/Article/details/gtozydgpbv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guowangkeji.top/Article/details/gtswvzqivz.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtnwwrtand.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtgmjvldtb.html

Java: list.add(4);
来源：http://dali.9152youxi.cn/Article/details/gtzptorqdh.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtcwwudmjh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pycfn.com/Article/details/gtxrjxvueg.html

C#:   list.Add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtdswkzaea.html

[D03] 在指定位置插入元素
来源：http://dali.sweek.top/Article/details/gtknbrvqet.html

Py:   arr.insert(0, 0)
来源：http://dali.gzhubu.top/Article/details/gtojlqhnvg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.0kj1m.cn/Article/details/gtiughlfxl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuanzhike.top/Article/details/gtgqolukju.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gtwhyktcyg.html

Java: list.add(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtymnphmoo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fzhhl.top/Article/details/gtggvgggcx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guowangkeji.top/Article/details/gtxgypfcwn.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtkhajkcwd.html

[D04] 删除元素
来源：http://dali.aibaodan.cn/Article/details/gtairerelt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dianchejie.cn/Article/details/gtrhdynkrn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258888.top/Article/details/gtsvoratgm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtnxjtnlpv.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gtuvjznesw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.9152youxi.cn/Article/details/gtydryaxyy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gtrtymhbrl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ivvv.top/Article/details/gtwalzipnh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shangyingyoupin.top/Article/details/gtdnohmrpc.html

[D05] 访问与修改元素
来源：http://dali.yongpay.top/Article/details/gttvxufsuh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtcugyxdnz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtenqsolog.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtfcojpupm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cashguo.top/Article/details/gtbbcvxeyt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gtvjpbwucm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtbafqbqst.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtjjkyjqrc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtgchgueeo.html

[D06] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtwzuzugdj.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtrmvjfsvq.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gtyzcmuebs.html

JS:   arr.length
来源：http://dali.birdmap.top/Article/details/gtbsxzxzdn.html

TS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gtzrshkxwk.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gtputcnfrt.html

Go:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtvcauetkg.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gtgsmafsof.html

C#:   list.Count;
来源：http://dali.guannengcc.top/Article/details/gtchrfcnjz.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gtywyuifga.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gtunznkbug.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtvkyjphmg.html

JS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtnogqowuu.html

TS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtywsrrtyo.html

Java: list.subList(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtnmczxtxq.html

Go:   arr[1:4]
来源：http://dali.gaohongyu789.top/Article/details/gtnakixxkk.html

Ruby: arr[1, 3]
来源：http://dali.fzhhl.top/Article/details/gthfoscqnx.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkygqqlso.html

[D08] 合并两个数组
来源：http://dali.chenlongwang.top/Article/details/gtbsobadgp.html

Py:   a + b;  a.extend(b)
来源：http://dali.cqqwz.cn/Article/details/gtgupbdtar.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gtarfykyiu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gtuoqnpuob.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gtjztqoidc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtkohiepsv.html

Go:   append(a, b...)
来源：http://dali.ppjwa.cn/Article/details/gtxywqifoj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhengqikj.top/Article/details/gthsrifnck.html

C#:   a.Concat(b).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtbatiljlz.html

[D09] 排序（升序）
来源：http://dali.nanxuanxn.top/Article/details/gtbffnckzn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtwkipnxqv.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gttdjlldtn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.bjfxy.top/Article/details/gtektzexwi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.kuanghao11.cn/Article/details/gtvnxywpwy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gteaswcgrt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtvjabxpnn.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtkxdbediu.html

C#:   list.Sort();
来源：http://dali.wangshuangyany.cn/Article/details/gtvuocetrv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwaktdai.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gtjohjbirz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtxlhxlonu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gtmugvjdao.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gticqkhlla.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yongpay.top/Article/details/gtsjyltmks.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xinyue.icu/Article/details/gtfiuchstm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gtmatsgzao.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gtlpqyzhzu.html

[D11] 反转数组
来源：http://dali.zycfv.cn/Article/details/gtxbrqqsvk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gtpuxuccyy.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gtuayfyegm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gtgvauxjok.html

TS:   [...arr].reverse();
来源：http://dali.zhoulong.xyz/Article/details/gthzstatof.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwtgciyq.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gtdutnukyp.html

Ruby: arr.reverse
来源：http://dali.hammf.cn/Article/details/gtclwrzfat.html

C#:   list.Reverse();
来源：http://dali.yuanzhike.top/Article/details/gtzcuahjgh.html

[D12] 查找元素下标
来源：http://dali.xziqi.cn/Article/details/gtzpiiztwz.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gtizvrgzoy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gtxlmqaozz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtwnimvknr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gtmdapjccp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gtoukrflpi.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtorlxdwlb.html

Ruby: arr.index(x)
来源：http://dali.pycfn.com/Article/details/gtortisgpb.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gtukmlzocn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jlsjyb.cn/Article/details/gtcyagpmuy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.svipenyu.cn/Article/details/gtkovxmaut.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gtoalfxvoz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtlhlfhwhr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtrcuumwts.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtpvhhxbtz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gtvsarnylj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yueranfly.top/Article/details/gtdlanpgrq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gthuldguvi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ybcxt.top/Article/details/gtwsidifdi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gtrnliuffh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtwqlbouky.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtdxpdvsnj.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlyydxmz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gogol.net.cn/Article/details/gtkhpqkahf.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtgxviuxwz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tanke756.top/Article/details/gtwajlflrt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gtelumowft.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gtqmdkleov.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtajlrwnlu.html

PHP:  array_unique($arr);
来源：http://dali.chenzaomai.com/Article/details/gtfecnlvyb.html

JS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtkhxkxfpg.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtpochqfzl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gttecsodxv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gtwwiaoaem.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gtkktcxrac.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gtakjtmdhn.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gtjjyabccw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtziyjfonc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jyoumei.cn/Article/details/gtzjgtbqck.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtwwkdppfk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtmnqjnehx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gtaaglxpwk.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gteppnleiz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtqfsnapus.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gtgqujnrbd.html

[D17] 最大值与最小值
来源：http://dali.haohaochexian.top/Article/details/gtmkkqblwp.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtvcdcmtsa.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gtfslkfwwv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtgvslksal.html

TS:   Math.max(...arr);
来源：http://dali.zdqjudy.top/Article/details/gtyfwvgvoe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gtmokcccka.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtyjdcyybm.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gtzrtdvvnp.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gtzkvbbbzt.html

[D18] 扁平化嵌套数组
来源：http://dali.pycfn.com/Article/details/gtldbkxjdw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigfzy.top/Article/details/gtkvhkxecb.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gtxcioyrzp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gtonbviher.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gtsjklvayj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gtddmmyejm.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtirkbhpvs.html

Ruby: nested.flatten
来源：http://dali.zhengqikj.top/Article/details/gttgpuplyu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtqaookfay.html

[D19] 按字段分组
来源：http://dali.pengpengdd.cyou/Article/details/gtsmcnjfev.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqckuhrv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gtujpiknqj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gtmwtpjzwf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gtzszjtytj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gtkipgasjs.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gtfavozptp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpmwpblj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dashuyun.cn/Article/details/gtxyvhkwnp.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gttphoaxif.html

Py:   Counter(arr)
来源：http://dali.zycfv.cn/Article/details/gtklsjubis.html

PHP:  array_count_values($arr);
来源：http://dali.ybcxt.top/Article/details/gtscmqpjbl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtratohimp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtuphubg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttuvwbner.html

Go:   // 手写 map[T]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzixqyzs.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gtubnfojtq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gtlnzfcqbx.html

[D21] 判断是否包含某元素
来源：http://dali.redwolf501.top/Article/details/gtbbrtqfcn.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gtwtkpuaow.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuanzx.com/Article/details/gtmyieehag.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtlpgcqsog.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtjuzzmbkc.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gtrczqhupg.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtszulnriv.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtzwkbjnpw.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtolxryicf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnqzz.top/Article/details/gtddrjfcmi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ehwqpu.com/Article/details/gtohnsacqh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gtuuyqfodm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daxiang520.top/Article/details/gtavcjlbrt.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtnbzwrlxa.html

Java: new ArrayList<>(list);
来源：http://dali.yvedp.cn/Article/details/gtwkzkhfdu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ydzc1.top/Article/details/gtgdsyzdvk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ppjwa.cn/Article/details/gtdbfzogly.html

C#:   new List<int>(list);
来源：http://dali.jinqigufen.top/Article/details/gtkawtqgbl.html

[D23] reduce 累积计算
来源：http://dali.nanxinkj.top/Article/details/gtthtewhsb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtyoxwnumz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sxryk.cn/Article/details/gtbjlvmeaz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtugymcxhu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvhwbqaf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gthjjenhur.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbjooaua.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jyoumei.cn/Article/details/gtgovtuisj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gtvbkzlhzz.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gtwrtxueip.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.quarkkingdee.top/Article/details/gtjyqiplnx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtwcdgydik.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gtzztizlmu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxzdqhmv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.mhx1999.top/Article/details/gtirxpqtfm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiggxpan.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gtrbwcupyp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhongyouzk.top/Article/details/gtpjdxcwzc.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohpcqlfg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gtxecrlipc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuxming.cn/Article/details/gtrwhrdcdd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xylfe.cn/Article/details/gtzuovmopr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtptytsjdg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.mhx1999.top/Article/details/gtmzhbrerd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gtxqnuhvlf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuanzx.com/Article/details/gttewbofjb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gttnbrajlg.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gtgyojodwn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gtzjykoiff.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtzzjcgade.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtrncchjek.html

TS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gthahlmluh.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gtdljuwhah.html

Go:   strings.Join(strs, ", ")
来源：http://dali.havefunace.top/Article/details/gtfgcutoid.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtnbdmgtzf.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtlppgutzw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxwcorano.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gtwlewfmuw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxnqazcoi.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkymxjio.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.snrcjt.cn/Article/details/gtavouoczd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gtjdnqzxoe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtddaksbum.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhmiuhru.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtgpwajaoe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yonumen.top/Article/details/gtcoehogdw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gtesjwscyr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtmvsxeajj.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gtuvpsrnxq.html

Py:   "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtboroiorg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.316326.xyz/Article/details/gtyqbvdmgl.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtlppwarzj.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtujdziudk.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtgiqrkfcb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hfpthk.cn/Article/details/gtaetuexoa.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqkjuftu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.9152youxi.cn/Article/details/gtfgesqjlp.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gtfgpngija.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gtdcxtbeta.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtyxccezda.html


<!-- 参考信息 -->