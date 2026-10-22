代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangdashe.top/Article/details/gtlkamqcdr.html

Ruby: -> { puts "run" }.call
来源：http://dali.jyoumei.cn/Article/details/gtdwlinvys.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shuidangran.top/Article/details/gtxjkjkyct.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gthhhzwpqt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtkhjhgbxv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtrovziakk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gtjjxczvyd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtaimtddet.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtkkeyflbm.html

Go:   func add(a, b int) int
来源：http://dali.hongshengwenyu.top/Article/details/gtbxlobewq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gtrpyltwah.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gtjpxdkunl.html

[C14] 泛型函数
来源：http://dali.gogol.net.cn/Article/details/gtcvuujgtv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangshuangyany.cn/Article/details/gtokxkhimo.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtkkealkxp.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtkbyoisgh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gtqmpzonti.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hysaishi.cn/Article/details/gtdnuqshqg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuxming.cn/Article/details/gtlunerxng.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtqjxqbfvc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gtkoiwhimb.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gtaugxoofv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtekxudafu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gthzkckyee.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtaaqwiiqb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtucaebovd.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtdhmarbsp.html

Go:   // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtnfukoaeq.html

Ruby: a, b = pair
来源：http://dali.yj20258.top/Article/details/gtbufthjns.html

C#:   var (a, b) = pair;
来源：http://dali.guowangkeji.top/Article/details/gttcvlbxgj.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gtmqimvavi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxinkj.top/Article/details/gtkapwxjir.html

PHP:  // 无重载
来源：http://dali.yj20258888.top/Article/details/gthkvciqsf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gtwrmvylvb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gtlvbrcynf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gtlgdvmkuy.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gtzcugswov.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sufxvd.cn/Article/details/gtsfxtpkey.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gtmpjvcchi.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtilvgpxga.html

D. 数组 / 列表 / 集合
来源：http://dali.bjfxy.top/Article/details/gtbvomtwaz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtkbjbsruo.html

[D01] 创建数组 / 列表
来源：http://dali.fzhhl.top/Article/details/gtwylesosg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.smart0.xyz/Article/details/gtxyhspptm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xinyue.icu/Article/details/gtyndgolbu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gtoxeazgue.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ivvv.top/Article/details/gtunimghif.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gtgqhiqyjq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.0kj1m.cn/Article/details/gtlmcfxzsx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gtnzqlmrix.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gtndvtqnes.html

[D02] 追加元素到末尾
来源：http://dali.jqgufenzy.top/Article/details/gtgtfudiyf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gthfpnwecm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gtmyikbmwf.html

JS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtfvpukpje.html

TS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtxvmihvvj.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gtudfxxppn.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gtibaxzojv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jianghu66.top/Article/details/gtrgnkizzf.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtmffswibs.html

[D03] 在指定位置插入元素
来源：http://dali.daxiang520.top/Article/details/gtswfggtrk.html

Py:   arr.insert(0, 0)
来源：http://dali.yvedp.cn/Article/details/gtrximbmzt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gtnbrvzmsp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gtosgdrnzg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtaceaekes.html

Java: list.add(0, 0);
来源：http://dali.yvedp.cn/Article/details/gtmcxcstvw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.mhx1999.top/Article/details/gtrpzfkvte.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guannengcc.top/Article/details/gtswkdwnfl.html

C#:   list.Insert(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtfpqcfbpu.html

[D04] 删除元素
来源：http://dali.guowangkeji.top/Article/details/gttezuzyuw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtfichhfix.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hammf.cn/Article/details/gtnftkevty.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gtwqoqfocr.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gtjugcvmrm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hysaishi.cn/Article/details/gtqtlbogrp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guannengcc.top/Article/details/gtbhnslemo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtqglfbthz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gtkbtuatuc.html

[D05] 访问与修改元素
来源：http://dali.hywenlv.cn/Article/details/gtpagymowj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gthvflehjo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gthmyelsuj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtvqpnvovt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuanzhike.top/Article/details/gtdzryracv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gtyhxusubw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtsejeltuu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtdaxcetjw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtgquffifa.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtgvqphsqv.html

Py:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtuknzbexa.html

PHP:  count($arr);
来源：http://dali.hnqzz.top/Article/details/gtqebylreq.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gtipopyajt.html

TS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtfllkeprt.html

Java: list.size();
来源：http://dali.snrcjt.cn/Article/details/gtslbkqglr.html

Go:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtflwdizug.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtnwjqkwzh.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gtxwknewtt.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtjdqicdgm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gtpxyqlskj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gtaqxybyvz.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtvugvapdn.html

TS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtmsepziks.html

Java: list.subList(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtpynikrzt.html

Go:   arr[1:4]
来源：http://dali.jlsjyb.cn/Article/details/gtmedctfkh.html

Ruby: arr[1, 3]
来源：http://dali.redwolf501.top/Article/details/gtavtlljgx.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtjgqdbtdp.html

[D08] 合并两个数组
来源：http://dali.shzxlz.cn/Article/details/gtkmsuhtvo.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gtrqhinidr.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwkysndg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gtdveofqkh.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gtnssrcoig.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gttismekzk.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gtedekiqqj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtiqzqlpow.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gtuhiurdcq.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwzcwvvu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtxiagimin.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gtxvzpgzrf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gtbdcazicv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gtnorrlziw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxinkj.top/Article/details/gtlgyumfwb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtysylllxe.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gtcoavryad.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gtxgasmpye.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gttzkgholk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gtdzplexwm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gthkgofnwa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtfchzxzcp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtifkjphjm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gthedrteaw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ydzc1.top/Article/details/gttwffssbo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gtfpjwmtgv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gtushunlqp.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gtuwcnikgs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gtehzztvdh.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbtxpbse.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtjlaxlpfo.html

TS:   [...arr].reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gtjqepfhwr.html

Java: Collections.reverse(list);
来源：http://dali.c1oappe.top/Article/details/gtybeudpvb.html

Go:   slices.Reverse(arr)
来源：http://dali.yonumen.top/Article/details/gtjmsnhtjw.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gtapzagstd.html

C#:   list.Reverse();
来源：http://dali.sysykeji.top/Article/details/gtusintxhs.html

[D12] 查找元素下标
来源：http://dali.zycfv.cn/Article/details/gtpsbxidbr.html

Py:   arr.index(x);  x in arr
来源：http://dali.gotoacloud.top/Article/details/gtoqztbsdj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gtluwdjlcz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtfvuordlp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gtinkkfwrk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgufenzy.top/Article/details/gtzozacmeg.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gtkmnnjxdc.html

Ruby: arr.index(x)
来源：http://dali.nanxuanxn.top/Article/details/gtbcnvqsol.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtwgnosvqw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gtdmrrxtma.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gtynoupwpc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cucudq.cn/Article/details/gtnfzinfau.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtkyxtkbyt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtbnormrrp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtvvfgoscz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtdircwivi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xziqi.cn/Article/details/gtzkbjuwew.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtcqtdtvzf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfomchyc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gttwvdypth.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gtaxbhgqxg.html

JS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gthjnqanky.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtpimlqfsm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gthqwqfvky.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtjedizaku.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtmgzjlpjx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtdgpjkxpa.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gtlxrhihel.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gtkjzbjnjl.html

PHP:  array_unique($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtnmsslgak.html

JS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtnlfvwdng.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtdefsmckk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gttgwrwwjj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgfzy.top/Article/details/gthmnabatg.html

Ruby: arr.uniq
来源：http://dali.ybcxt.top/Article/details/gtumpbkbkv.html

C#:   list.Distinct().ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtitvpxexk.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gtposnpzkf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtyfpefwkd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuanzhike.top/Article/details/gttanbnlwx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtfkkcukwy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtcakdcjwt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gtulkndwpj.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gtsyityouv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gttnzvppvw.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnqzz.top/Article/details/gtwhjksgod.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gtkavsrsta.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gtnvgqtyit.html

PHP:  max($arr);  min($arr);
来源：http://dali.yueranfly.top/Article/details/gthjzitmui.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gtjgqzmcff.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gtdkyssbzu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gtzfpegtzl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.bjfxy.top/Article/details/gtqkwygjah.html

Ruby: arr.max;  arr.min
来源：http://dali.kuanghao11.cn/Article/details/gtwmqkfoxz.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtxmtpfaiu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gthlrdybrp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yongpay.top/Article/details/gtpbfoafrn.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gtirbqtycb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gtqtjgmhpy.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gtgdsuzote.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gtlruebskq.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gtssctnarq.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtxjnlctdf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtoeqthehl.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gtonipomzs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtqksufbtx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gthoewymei.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gtbmhclmtx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarpzfjlb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gtqtqhflaa.html

Go:   // 手写 map[string][]T
来源：http://dali.jianghu66.top/Article/details/gtqaqhaffy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gtejerrjfr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.mhx1999.top/Article/details/gtmegcnsvi.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gtrgcmcxhw.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gttgaaqons.html

PHP:  array_count_values($arr);
来源：http://dali.0kj1m.cn/Article/details/gtcusspppc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgosmbvzl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtgjqyyqds.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gtdsgpcjjo.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gtwzmmcvoe.html

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gtishvrugo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgrkoxic.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gtsuhaepja.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxshfhbo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgfzy.top/Article/details/gtidctyrtz.html

JS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtbztmmnki.html

TS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtyejhzioi.html

Java: list.contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtfeckpxtg.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtoahkpezj.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtvjyesmtm.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gtyehzyfxi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gthfyuunsc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gtcaqsmckj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ydzc1.top/Article/details/gthpgnmwxo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtwzivbonr.html

TS:   [...arr];
来源：http://dali.ivvv.top/Article/details/gtjzznbxmo.html

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gtojktdjqk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.kuanghao11.cn/Article/details/gtjultbvct.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangdashe.top/Article/details/gtiakbesgu.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtknwrpsdb.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gtgdootyqa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.svipenyu.cn/Article/details/gttcrvdrfo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtblaqhztz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtucayexvj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gthpenpwnq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gtnhjimucu.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtvaipznvv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gtfwqjbjln.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gthlqzztoa.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gtxclpmctu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtnwgixeqm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gtyvyajhbz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgzgcvgo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtqrnrobyo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gttwlcdlil.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gtqjgtrrts.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlziuljyz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xziqi.cn/Article/details/gtvcynhlyy.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gtwapqnvcc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gtpdmmakbl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gtszpmtfak.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ehwqpu.com/Article/details/gtpvgevguf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gtmwzxmgik.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.havefunace.top/Article/details/gtzylqxmzo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtkkqkruzq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.redwolf501.top/Article/details/gtkfceiebw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtqgbycspl.html

[D26] 数组转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtvmrrfyns.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtnpepaxrl.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gtmlilyvvm.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtmmkcrvtj.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gthcecdgxf.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtnsvwjxij.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gtxosjemih.html

Ruby: arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtncrhjtwj.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtpllknhrw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtxsxeshga.html

E. 字符串处理
来源：http://dali.shangyingyoupin.top/Article/details/gtiaazujgy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtnupnkdyt.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtqsyzvmbb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiynthnfl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gzhubu.top/Article/details/gtfheylriq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gtpjnfvxij.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtwpqnjuto.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gtynzfgyhx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pycfn.com/Article/details/gtsjfqhclx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterdgmfta.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gthbhwztiy.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gtilmgeyiy.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtsidarqbd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtsjsyaeeu.html

JS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtbmjkvwrv.html

TS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtmvlxtzde.html

Java: "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtgkcbkzmk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sysykeji.top/Article/details/gteibvsolg.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtmzlzqrjt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yongpay.top/Article/details/gtxeiygpta.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtxblyxeke.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gtbllzgrsp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gthgqwceyz.html


<!-- 参考信息 -->