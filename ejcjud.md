代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gtupyweuzr.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gtllxymnxd.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenjidiqi.icu/Article/details/gtrcjxmjjd.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gtiifmxumw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuanzx.com/Article/details/gtddncyxpj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtshrmzruo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gthtwqonss.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daxiang520.top/Article/details/gtxpuemwgp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ehwqpu.com/Article/details/gtovfxvmej.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtopdtimhh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtfugmiitm.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuanzhike.top/Article/details/gtnifehhzw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sufxvd.cn/Article/details/gtfwtslqwa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtonompjgq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gtpxfpwxpp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gthgshznyg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtepgzncmw.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gthhrvpakc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gteldbbdxi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gtbtmmrcii.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gtnbwhyuuh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gtlqdtmoso.html

PHP:  // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtlmgqbges.html

JS:   // 无泛型
来源：http://dali.yj20258.top/Article/details/gtgmploimr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gtznjobptk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gtuszdxvnk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jyoumei.cn/Article/details/gtwbsqdqlg.html

Ruby: # 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtbtwhecnl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gtvvapotaa.html

[C15] 解构 / 展开参数
来源：http://dali.zycfv.cn/Article/details/gtnqolifnl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gtaavejlkd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gtwyioejir.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gttiikjhvr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gtwynbfqzm.html

Java: // 无解构
来源：http://dali.xuanzx.com/Article/details/gtsnccapan.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gtbmzznqda.html

Ruby: a, b = pair
来源：http://dali.feifeiyinyue.top/Article/details/gtnnrjthyi.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkfqxfmx.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gtbrbaeadn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gtccjggurj.html

PHP:  // 无重载
来源：http://dali.bjfxy.top/Article/details/gtyuiwzvlu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gtfzpcingk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guannengcc.top/Article/details/gtbluacxiv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hfpthk.cn/Article/details/gtvmmbyvjg.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhqqbgzs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tianlin.xyz/Article/details/gttienwdkc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtdlwgpeav.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtyppdfbrh.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gtuymitkpl.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtlhseflol.html

[D01] 创建数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtoapfnajx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gtzrmpdfqo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gtfdqdmext.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtqaxbuwca.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gtmvlrdtly.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gtodtdqdjo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shzxlz.cn/Article/details/gtlffzrbiv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guowangkeji.top/Article/details/gttisszhcz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gzhubu.top/Article/details/gtqczgkfdj.html

[D02] 追加元素到末尾
来源：http://dali.meibo888.top/Article/details/gtvipalwlh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gttickvljs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ppjwa.cn/Article/details/gtxhbbzaps.html

JS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gttujqtshc.html

TS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtdaqncjxz.html

Java: list.add(4);
来源：http://dali.316326.xyz/Article/details/gtiwsnkubm.html

Go:   arr = append(arr, 4)
来源：http://dali.havefunace.top/Article/details/gtcomvfpgw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gtwhcyeaym.html

C#:   list.Add(4);
来源：http://dali.yongpay.top/Article/details/gtnhrhhqjs.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gteoivngcz.html

Py:   arr.insert(0, 0)
来源：http://dali.smart0.xyz/Article/details/gtpyznodrp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzwkzuno.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gtooefkbko.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aizwys.cn/Article/details/gtgecmirzu.html

Java: list.add(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtcdvwsezp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gtwqrmbant.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtxpqrjuci.html

C#:   list.Insert(0, 0);
来源：http://dali.gzhubu.top/Article/details/gtpedrzjgj.html

[D04] 删除元素
来源：http://dali.0kj1m.cn/Article/details/gtmzuyaaxd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sysykeji.top/Article/details/gtovojmzbk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.haohaochexian.top/Article/details/gtblnenyud.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dashuyun.cn/Article/details/gtjschsxwp.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gtrcxqfcsa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenzaomai.com/Article/details/gtjessfrvy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aibaodan.cn/Article/details/gtibdwsyqq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gtylzzmsbe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.mhx1999.top/Article/details/gtvmrjwile.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gthsrvoibc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtcnqmyyxz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtnmmbwzox.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtzmzwutlg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guowangkeji.top/Article/details/gtogizszme.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gtvjgxoaqm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtdnmzjgef.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtulvevxmj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtmlvfwpgs.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtorkrudwy.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtcrgfqsnt.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtuztwahwu.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtbfgqjgaz.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gthaeuvktd.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gtobvcxoox.html

Go:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtlsdsytni.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gtbehhniep.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gtwrtpfbhl.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gtndvuagaa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gtjffkqaaj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gtxggsixdk.html

JS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtruxjsqrq.html

TS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gthdzoxubl.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gthjceukys.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gthikvpxtf.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gtfprengmx.html

C#:   list.GetRange(1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtadumgagc.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gtozdpqqvm.html

Py:   a + b;  a.extend(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtffruqqbm.html

PHP:  array_merge($a, $b);
来源：http://dali.xuanzx.com/Article/details/gtryghikmv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ivvv.top/Article/details/gttmcyugjx.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gtnstetgga.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yonumen.top/Article/details/gthqmltlyg.html

Go:   append(a, b...)
来源：http://dali.0kj1m.cn/Article/details/gtbfwyeowq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ybcxt.top/Article/details/gtknsutvpf.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtoqamqtec.html

[D09] 排序（升序）
来源：http://dali.jyoumei.cn/Article/details/gtaccqgjtk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyhtglww.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtmgmcoagd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnqzz.top/Article/details/gtjwscewar.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogbiepzw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tianlin.xyz/Article/details/gtlecbfyic.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtcojivayj.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gtzdhpodka.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gtyqqignfr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.kuanghao11.cn/Article/details/gtwzbezubh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dianchejie.cn/Article/details/gtnpegjyzr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtrzsedfvp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gtsprfoliq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gthjvbgyvr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xylfe.cn/Article/details/gtnuzzrdfa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojnxamdy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pengpengdd.cyou/Article/details/gtgbgtrwai.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gtcgvofbot.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gtdrmhmwvq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xziqi.cn/Article/details/gtgnkizbnz.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gtftcqqotj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtqtsgtoqb.html

TS:   [...arr].reverse();
来源：http://dali.zhixingplan.top/Article/details/gttcoqztmd.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtcoqedvjf.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gtrqakmhyv.html

Ruby: arr.reverse
来源：http://dali.ppjwa.cn/Article/details/gtapjgdzkb.html

C#:   list.Reverse();
来源：http://dali.ppjwa.cn/Article/details/gtqjfupona.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gthiiroklk.html

Py:   arr.index(x);  x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtohoprdgt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shzxlz.cn/Article/details/gtqkpbvppc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtweyzteot.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtrmtuccxb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gtcsdbvrgv.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gtdotzfflz.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gtoupfszms.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gtiqdvgfkz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cqqwz.cn/Article/details/gtmgrpsrxt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gtogtfcyjx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cucudq.cn/Article/details/gthndlvmrj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gtvnvadpgm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtkmvtlppe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbhehrsm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.feifeiyinyue.top/Article/details/gttypjhvfp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gtetrqsarf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtcwbuvgzc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yueranfly.top/Article/details/gtmacflcht.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnqzz.top/Article/details/gtuqhnxwgn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.bjfxy.top/Article/details/gtdhrmnsxj.html

JS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gtmhbtivlc.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtohpmsbtv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shuidangran.top/Article/details/gtvggjifjx.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtfxrjtutw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtuqazebmq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gzhubu.top/Article/details/gtdiccwgoy.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gtykxilrbm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gtzvtehuwv.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gtfkhwhhnd.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtvrfnghbp.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtxfzwpqav.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgufenzy.top/Article/details/gtqhntvcmv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbcqhuqi.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gtojxlcigl.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtikrakino.html

[D16] 求和与平均值
来源：http://dali.gzhubu.top/Article/details/gtlcelecpe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gtjatpbbyo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtqgxtjibw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwconnfxp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtsmmartkv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yongpay.top/Article/details/gtxdmokiot.html

Go:   // 手写循环累加
来源：http://dali.hnxiangtu.top/Article/details/gtkqjeydex.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtekmhergy.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gtjwqvpsha.html

[D17] 最大值与最小值
来源：http://dali.chenzaomai.com/Article/details/gtknxqyups.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtntmsbtvy.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gtrndxboet.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkpcxgrh.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gtoixiwjcf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtogslaigs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gtnbnohnxu.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gtkdmxgfto.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gtsougyygu.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gtkfvhskzk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfiyetewq.html

PHP:  array_merge(...$nested);
来源：http://dali.hammf.cn/Article/details/gtjlccxneu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gtrusvizud.html

TS:   nested.flat();
来源：http://dali.quarkkingdee.top/Article/details/gtsmcpoqqc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtldfgnzfy.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gtaivoezmy.html

Ruby: nested.flatten
来源：http://dali.jinqigufen.top/Article/details/gtjfzhhozq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuptbnjah.html

[D19] 按字段分组
来源：http://dali.havefunace.top/Article/details/gtqfzkokjb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gtarjuarrm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gaohongyu789.top/Article/details/gtzlsxugmg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gzhubu.top/Article/details/gtdwztidsk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gtjpvgpueb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gtqvkziece.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgfzy.top/Article/details/gtazmqikxe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.quarkkingdee.top/Article/details/gtdzljwqcz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhiwuduotai.top/Article/details/gtqvjjrmza.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gtitgxsirs.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtyrwxwrcn.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gtgqyycqgy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gtnrjlaiiq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtumenlase.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gtjptdiuyh.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gtcobzozjf.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gtqtetsfcb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gtryxdhbzv.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gtgbyywelm.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivbebgxg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gtrgwzgjxp.html

JS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtxsqvigkt.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpucvcnb.html

Java: list.contains(x)
来源：http://dali.yj20258.top/Article/details/gtaayrsvpw.html

Go:   slices.Contains(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtrrlfbdsi.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gtmwljshcx.html

C#:   list.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtwasflcmh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuanzhike.top/Article/details/gtmvefdpkz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtdfqbzvmx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gtzwhdplll.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gttqsscddw.html

TS:   [...arr];
来源：http://dali.cqqwz.cn/Article/details/gtqmokdcow.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gtzuogtjqy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xziqi.cn/Article/details/gtpsmmpste.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrzlxswv.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gtouhsckjo.html

[D23] reduce 累积计算
来源：http://dali.yonumen.top/Article/details/gtgbcbutnp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yangfankeji.com/Article/details/gtcmmkoggy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gtewbfrjrj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gtgzlliicu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtkuvycifj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gtvgxtrnrf.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuibsujh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jyoumei.cn/Article/details/gtczmkrwoj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtdknxcwmi.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuxming.cn/Article/details/gtnxivxvti.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gtuvqelblz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gteeparcfv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gtokyyklbr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtmgrgbzfi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gtlaxsvnzo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxuanxn.top/Article/details/gtuemdkpxx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nwbrower.top/Article/details/gtnscxxwrj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gtmjsiwwnj.html

[D25] Set 集合去重与交并差
来源：http://dali.dashuyun.cn/Article/details/gtlqqnxwda.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gtqohlfmpx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sxryk.cn/Article/details/gtxkuwjkfl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gtlgbyvrgu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gtnclbfvug.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258.top/Article/details/gtrdxlungx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhongyouzk.top/Article/details/gttjiirpze.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gtoqayqkwt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cdnleiting.top/Article/details/gtwspenqqy.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gtojcclymh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gtmnvwdplf.html

PHP:  implode(", ", $arr);
来源：http://dali.xuanzx.com/Article/details/gtaujlwvmt.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtuqyvpkxd.html

TS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtkroequzz.html

Java: String.join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtgcfyzq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjnshylg.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtvayytmik.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtysdjjcay.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlmihgwxi.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtxidkdkyq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtblwfwq.html

[E01] 拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtrseftfgw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gtydvchcta.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gtktxhtztb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gtcmvwqbgl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtthkmcsat.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gtrxaoyixn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xylfe.cn/Article/details/gtfsvctkuo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gtvkgdbanb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtumkxtscn.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gtxqzflyau.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtdqvmwelu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gthzrwgkgn.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtgjflmiix.html


<!-- 参考信息 -->