代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gtgaotkrcw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtqwwtolwg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sysykeji.top/Article/details/gtjuupqvog.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtpwszeixe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjvoihson.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gtbxlsfzpg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnuxboaa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hfpthk.cn/Article/details/gtvrpaxqoh.html

[C14] 泛型函数
来源：http://dali.yj202588.top/Article/details/gtxkycktvo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.feifeiyinyue.top/Article/details/gttqgivvah.html

PHP:  // 无泛型
来源：http://dali.ivvv.top/Article/details/gtdypcegjm.html

JS:   // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtmaudbzxo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangdashe.top/Article/details/gtcmoexhxt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gtnuyoggbj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhixingplan.top/Article/details/gteuqbadsa.html

Ruby: # 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtcfzoowlo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yongpay.top/Article/details/gtawqgptbw.html

[C15] 解构 / 展开参数
来源：http://dali.aizwys.cn/Article/details/gtdegkvxbr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gtedsqedan.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtoavtsccx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gthfudxulx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gtlrqaehol.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gtnngdtqlb.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gtwrtevlgg.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtmtheygtc.html

C#:   var (a, b) = pair;
来源：http://dali.gotoacloud.top/Article/details/gtdqfnrcbg.html

[C16] 函数 / 方法重载
来源：http://dali.chenjidiqi.icu/Article/details/gtzpbsiuvx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zdqjudy.top/Article/details/gthdbkmrop.html

PHP:  // 无重载
来源：http://dali.jqgufenzy.top/Article/details/gtdmzoxdcj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gtgudvjkmc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gtzchkjnyi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hysaishi.cn/Article/details/gtskqkcogt.html

Go:   // 无重载：用不同函数名
来源：http://dali.xinyue.icu/Article/details/gtwmccuwjj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxinkj.top/Article/details/gtzvsdmthv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.9152youxi.cn/Article/details/gtreiiiatg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtrjnseftf.html

D. 数组 / 列表 / 集合
来源：http://dali.yuanzhike.top/Article/details/gtamaumlsn.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtkmelanmf.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtepdauxxp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gtfsogpjsu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gtvgidcagj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtywbtfykz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgufenzy.top/Article/details/gtgyiiqpvv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenjidiqi.icu/Article/details/gtewumifty.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gttdvqbedx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtmuzgjeew.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gtovfzinrj.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtvzrahblf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pycfn.com/Article/details/gtltvphbkq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gtducjayzl.html

JS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzmmvmpi.html

TS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gtsqxxjmei.html

Java: list.add(4);
来源：http://dali.yj20258.top/Article/details/gtpzrogbla.html

Go:   arr = append(arr, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadirsqkb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gturqcetbm.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztlandtj.html

[D03] 在指定位置插入元素
来源：http://dali.shuidangran.top/Article/details/gtacnxhbar.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gttdltngle.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj202588.top/Article/details/gtzunxloux.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gogol.net.cn/Article/details/gtdkmhhzoe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtgrbihtfj.html

Java: list.add(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtfbxsmrzu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtopybhhsl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hysaishi.cn/Article/details/gtrzwfozxj.html

C#:   list.Insert(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtjaqvicwu.html

[D04] 删除元素
来源：http://dali.0kj1m.cn/Article/details/gtybonfjjv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gtslqraelr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gtsamwgsqa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shangyingyoupin.top/Article/details/gtfsdmiotv.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtxfbcnidy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.havefunace.top/Article/details/gthcknpcxo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hammf.cn/Article/details/gtketavcxk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258.top/Article/details/gtxbrpycqr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxinkj.top/Article/details/gtogvjcyxd.html

[D05] 访问与修改元素
来源：http://dali.jqgufenzy.top/Article/details/gtxhdxooyp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtmigtnzqu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtlpzfgfwd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtcjqcuvkz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.smart0.xyz/Article/details/gtbrozlaxk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gttmsjszji.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtpundncnp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtqoqvuyvb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtgsalljep.html

[D06] 数组长度
来源：http://dali.birdmap.top/Article/details/gtqphonxdi.html

Py:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgqnyhkk.html

PHP:  count($arr);
来源：http://dali.yueranfly.top/Article/details/gtlymfaivv.html

JS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtbffqmxmk.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtlmoouuli.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gtldmdrgzf.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtxudxmrbs.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtlsozrvik.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gteeyqzvka.html

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gtyhhwtxer.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gtrmuyipzg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtaldlaghj.html

JS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gteczduihg.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtzhzmsvwu.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtmwrwqrgg.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gttkfpbshw.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtywfzykyx.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtjryikxhv.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gtxtrrfbry.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenzaomai.com/Article/details/gtmfypbsui.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtsnjghwdy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gtvtixjcdv.html

TS:   [...a, ...b];
来源：http://dali.guannengcc.top/Article/details/gtysyfvqis.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gtvktgksvy.html

Go:   append(a, b...)
来源：http://dali.jqgfzy.top/Article/details/gtieheapor.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gtjpbgfgxy.html

C#:   a.Concat(b).ToList()
来源：http://dali.sysykeji.top/Article/details/gtgotfbvif.html

[D09] 排序（升序）
来源：http://dali.0kj1m.cn/Article/details/gtyhpketvz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtfmeqpzel.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gtikkexloz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yangfankeji.com/Article/details/gtukjgtefg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gtcyzctukp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shangyingyoupin.top/Article/details/gtydgupvgw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtxahpynsn.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckrebhhk.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gtqwqukzit.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqikzmsu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gtmgtgueee.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtzawbpmga.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtcowyuyfr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gthpatrjnz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuanzx.com/Article/details/gtujjzqstq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gtfrjvjyil.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpsyotzb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gtrqpgyzhy.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gtlmynqkyu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gtssmaoviz.html

PHP:  array_reverse($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjimylgok.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gthporllvr.html

TS:   [...arr].reverse();
来源：http://dali.redwolf501.top/Article/details/gtlcbvfbps.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtziyoitkt.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gtpplbcjyd.html

Ruby: arr.reverse
来源：http://dali.yangfankeji.com/Article/details/gtsfjmoouc.html

C#:   list.Reverse();
来源：http://dali.daxiang520.top/Article/details/gtjyrkgttc.html

[D12] 查找元素下标
来源：http://dali.haohaochexian.top/Article/details/gttgjqsmtm.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gtqtsbibfh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtfyqtiydt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnatftzin.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtbicirvzm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gtcwodxyio.html

Go:   slices.Index(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtcgvzhaws.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gtgejjaklr.html

C#:   list.IndexOf(x);
来源：http://dali.xylfe.cn/Article/details/gtfwjcfzvj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jianghu66.top/Article/details/gthsouqedn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guowangkeji.top/Article/details/gtlkyncpkf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gtotcazder.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtecvningj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtljlrrwdp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtgdfgcaoq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.snrcjt.cn/Article/details/gtaqflhelp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuanzx.com/Article/details/gtaonejewm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gtbffjbawp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gterseogxt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.mhx1999.top/Article/details/gtcuzuraeo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtjpgibhqt.html

JS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtwnxfkgcn.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtzfhalmjx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yanxiufei.cn/Article/details/gteondtpfc.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtatezowwa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofcblwmf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gtioomsgkm.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtapgkcedw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtgdqezahk.html

PHP:  array_unique($arr);
来源：http://dali.jqgfzy.top/Article/details/gtxczbbjfz.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtvvbbwaqh.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtdvrvqzqu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yueranfly.top/Article/details/gtltltykas.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gthlwhkcpz.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gtrskkdbbt.html

C#:   list.Distinct().ToList()
来源：http://dali.fzhhl.top/Article/details/gtbvvfreit.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gtmzphtkrd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gtdtnpcjfe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gtmcfsioof.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtmbfxrbri.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtxtrbhgjc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gtfoeemdzb.html

Go:   // 手写循环累加
来源：http://dali.chenlongwang.top/Article/details/gttalbsnzv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gtzqsjvrbc.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnqzz.top/Article/details/gteimaatrj.html

[D17] 最大值与最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpafsyyu.html

Py:   max(arr);  min(arr)
来源：http://dali.yonumen.top/Article/details/gthnmdatpn.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtqyzfhhui.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jyoumei.cn/Article/details/gthyafxdus.html

TS:   Math.max(...arr);
来源：http://dali.dashuyun.cn/Article/details/gthvujqdjk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gtqwyfzwef.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfwxkpal.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtskhpvybf.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gtrhmtjvyc.html

[D18] 扁平化嵌套数组
来源：http://dali.redwolf501.top/Article/details/gttnjigrpq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigfzy.top/Article/details/gtqdfcygnu.html

PHP:  array_merge(...$nested);
来源：http://dali.ppjwa.cn/Article/details/gtgdoqeaon.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gtvutixyoj.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gtlpuxbwzt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gtmnncpcbw.html

Go:   // 手写双层循环
来源：http://dali.hongshengwenyu.top/Article/details/gtknpifmfl.html

Ruby: nested.flatten
来源：http://dali.nanxinkj.top/Article/details/gthtolvfar.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gttcepiovf.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gtkkdsnzsn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtwumeqhkv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jianghu66.top/Article/details/gtbibgdbcm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhiwuduotai.top/Article/details/gtkxfbpdqw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gtcrbdfuxb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gtxpxzcyie.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gtjoattnhf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnqzz.top/Article/details/gtkmuhhszk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmikojsdd.html

[D20] 统计每个元素出现次数
来源：http://dali.redwolf501.top/Article/details/gthtfmeozz.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gtgjpnuzil.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtqdgxhbyk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtggzkrkqj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtzesbamli.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gtxbovwrtx.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gtulwkhuzw.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gtgtujquct.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gtiltdydgc.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtarxjomcq.html

Py:   x in arr
来源：http://dali.ppjwa.cn/Article/details/gtihvrhzkn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gtrzcgxzjr.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtcgswkozz.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtbdwrpqfa.html

Java: list.contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtwbqtdmqu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtnujsdbmc.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdlcvbty.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtmfzmyidt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gtdoqjtnjc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jyoumei.cn/Article/details/gtvupkcdgw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenjidiqi.icu/Article/details/gtmakflkfy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzanerytg.html

TS:   [...arr];
来源：http://dali.nanxinkj.top/Article/details/gteqrisazs.html

Java: new ArrayList<>(list);
来源：http://dali.andypj.xyz/Article/details/gtnywxrnxt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtahuystai.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gtubajwqxw.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gtwkdfdvub.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gteoglzswx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sysykeji.top/Article/details/gtozfuboiz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gtkqdmmpgr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gtxduluuof.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtwjzcxham.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gtigfjwkrf.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtdyahglrm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gtsxfhmkmj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gtlqzxeqdq.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtwnunqpgo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gtziienthy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtvdkqjtfh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258888.top/Article/details/gtxnseqqcv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gteuxzosvl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.kuanghao11.cn/Article/details/gtlnxycxoo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gtwnitywcd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuxming.cn/Article/details/gtugbdmkdn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ivvv.top/Article/details/gtbzkwvuhf.html

[D25] Set 集合去重与交并差
来源：http://dali.gogol.net.cn/Article/details/gtycmuiayz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gtdhhhhpth.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daria6918.cn/Article/details/gttbwvptlx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpafisyve.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuxming.cn/Article/details/gtufhntwqo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtjmczzono.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gzhubu.top/Article/details/gtepvfjsgg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hywenlv.cn/Article/details/gtibmtlrtp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gtosqzztse.html

[D26] 数组转字符串
来源：http://dali.dashuyun.cn/Article/details/gtdgqvhhpf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gthjocvelv.html

PHP:  implode(", ", $arr);
来源：http://dali.hammf.cn/Article/details/gtnkjefcyj.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtbwsdjxyg.html

TS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtgbqohcun.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtdkbtreok.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigufen.top/Article/details/gtoggryqrc.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtjltraggw.html

C#:   string.Join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtpjchsxww.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtsppcynee.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmodwton.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxbzcalhl.html

[E01] 拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtkcycuulc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gtvzjogjkh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gthfoixaog.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtnxmydxwh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtaalgazzp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gtqsrsoxxm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gtjbwwatzf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gtnopbpwpd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtubgwdyeg.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gtcoaahlbz.html

Py:   "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gtbzmeodjs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhengqikj.top/Article/details/gtekwqmjxd.html

JS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtmlgodmbv.html

TS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtnulrqjvi.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtqkatgnoa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yangfankeji.com/Article/details/gtjjmjlsoa.html

Ruby: "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmjkstbb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgfzy.top/Article/details/gtfwqqtafp.html

[E03] 截取子串
来源：http://dali.nwbrower.top/Article/details/gtiimuxisl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gtvihabvbo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtwqcqzgjk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtbqzoowtd.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtpqsfdrlk.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtdiifewyt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pycfn.com/Article/details/gtpojpdlqp.html


<!-- 参考信息 -->