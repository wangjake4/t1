代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtuzdzicij.html

Go:   func add(a, b int) int
来源：http://dali.yvedp.cn/Article/details/gtfpwhnpzb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gtdzityite.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gtchrugraa.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gtzsfvqvyx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtiqugatgg.html

PHP:  // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtbqlblvuh.html

JS:   // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtoztsrcqt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagsqhnfu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hfpthk.cn/Article/details/gtuzapdrnr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gtzvseoonw.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqzxpdhw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinghuilouyu.cn/Article/details/gtexucqvkk.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gtwrfwxtrm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtwvunnzov.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gtbeawcunh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdnskzcd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtbrnqihtz.html

Java: // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtfmfoliue.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtznykkwfj.html

Ruby: a, b = pair
来源：http://dali.yj202588.top/Article/details/gtvhpyyzhz.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gtvxkfwzua.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtajunfpwv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gtfxpxtsdo.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gtkxrcyjiu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gtdbsgxaos.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gtfoxelufe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzspskkcv.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangdashe.top/Article/details/gtruqehsyo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gtaklawnfm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.meibo888.top/Article/details/gtukjqygvm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gturwqunii.html

D. 数组 / 列表 / 集合
来源：http://dali.ybcxt.top/Article/details/gtftiujvew.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtzzhakbwx.html

[D01] 创建数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gtzxtqlsvz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gtetvvhshk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtbaxghmln.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.smart0.xyz/Article/details/gtxbsggesd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gtthuwxhwi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gtqvashsbh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenjidiqi.icu/Article/details/gtarjwzgre.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ehwqpu.com/Article/details/gtniovlqgv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.smart0.xyz/Article/details/gtyzjnoueu.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gttxbfvhby.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafgpkjye.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zdqjudy.top/Article/details/gtstwgkodu.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtralezzym.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gttrecetkq.html

Java: list.add(4);
来源：http://dali.zhoulong.xyz/Article/details/gtxamkxvzy.html

Go:   arr = append(arr, 4)
来源：http://dali.gotoacloud.top/Article/details/gtoescedhn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.bjfxy.top/Article/details/gtskarcead.html

C#:   list.Add(4);
来源：http://dali.zhoulong.xyz/Article/details/gtkgwlaicw.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gtklxgkqfs.html

Py:   arr.insert(0, 0)
来源：http://dali.c1oappe.top/Article/details/gtplztbuaw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ppjwa.cn/Article/details/gtswqoufyd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtgktidgkm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtjrdzrjnq.html

Java: list.add(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtigpyjwuk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aizwys.cn/Article/details/gtwqudaylk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gtizmaewiz.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtmhcuvrog.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gtojoslpiw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfffxudh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwvpfhqp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ivvv.top/Article/details/gtzvxwtcho.html

TS:   arr.splice(0, 1);
来源：http://dali.c1oappe.top/Article/details/gtnbdopgaw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yueranfly.top/Article/details/gtucyydwhz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtsquarkvz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gtlstidenw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.svipenyu.cn/Article/details/gtiupkjfof.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gtoudvhiwk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtglfawbht.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtkolnhfzz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtzerrypsn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pengpengdd.cyou/Article/details/gtjbytzbjg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gteppqlplo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtaasmwqid.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtcsdewwzy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtaxsyuqhd.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtewcnahne.html

Py:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtirlvqwso.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gtfxmjcmwm.html

JS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gtafpxwlin.html

TS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gtnpwkbltw.html

Java: list.size();
来源：http://dali.yvedp.cn/Article/details/gtwdphkjfs.html

Go:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gtnxxajtvp.html

Ruby: arr.length; arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtjjrivrkb.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gtfibbjkaq.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gtgrvjxbak.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gtjtpqliux.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gtvenzxmax.html

JS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiizubbx.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtxboqouwr.html

Java: list.subList(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtqqhzjfcy.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gtwcyvdaqs.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtuqfgtyzg.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gttcogmyqi.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpimfpkfo.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gtlpvffnvf.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gtstcmggej.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.kuanghao11.cn/Article/details/gtgvwdiphu.html

TS:   [...a, ...b];
来源：http://dali.dianchejie.cn/Article/details/gtgucwgmas.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gotoacloud.top/Article/details/gtdvkniylp.html

Go:   append(a, b...)
来源：http://dali.haohaochexian.top/Article/details/gtvztyimms.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhoulong.xyz/Article/details/gtxldgsnbf.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gtzlwlxnqy.html

[D09] 排序（升序）
来源：http://dali.aibaodan.cn/Article/details/gtytncvxkw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtgrmlpayc.html

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gtgygvnlim.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtuwocpchz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuxming.cn/Article/details/gtlcdcouiv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuxming.cn/Article/details/gtdrtjjtrv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtxtfkcvfv.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtcljsyxfd.html

C#:   list.Sort();
来源：http://dali.daxiang520.top/Article/details/gtkucrssmq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtbuwkyxsv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gtdqrbakpq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtaoccmlfa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtctkyvfen.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtbkvxdtwl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.svipenyu.cn/Article/details/gtrdsbhmnb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gtmhuznfhb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gtoafaanaq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gtzvdjcvlx.html

[D11] 反转数组
来源：http://dali.cucudq.cn/Article/details/gtgxrabpwr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gtxbeachfp.html

PHP:  array_reverse($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdczwhzxs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jiagoushi.top/Article/details/gthbgusmku.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtuaugctiy.html

Java: Collections.reverse(list);
来源：http://dali.yueranfly.top/Article/details/gtsbajygib.html

Go:   slices.Reverse(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtozzfozer.html

Ruby: arr.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtmdmjwuxz.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gtymvzolqz.html

[D12] 查找元素下标
来源：http://dali.ydzc1.top/Article/details/gtndopxxfd.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtrengugpm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guannengcc.top/Article/details/gtagqjrhfh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtlqtrgrtq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtzxlvwaoz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yanxiufei.cn/Article/details/gtqajhvrli.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtkkmztlsz.html

Ruby: arr.index(x)
来源：http://dali.jinqigfzy.top/Article/details/gtsrqdcxnk.html

C#:   list.IndexOf(x);
来源：http://dali.ivvv.top/Article/details/gtuabcsocm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gtfdkttdpy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gtaqlzgurc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dianchejie.cn/Article/details/gthngfkupv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtlcvdcdhg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbfjkldc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gtcztsxmfb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gtrmfdaqpd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbaaanye.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtqqyecspp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yangfankeji.com/Article/details/gtsnefsatt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gtviklmawv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gttexfttvv.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtsefkscup.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtmmropzoe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnqzz.top/Article/details/gtovpixiwq.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtwipkoxqn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtxlrfboxn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtsvoeqyqj.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gtpmewazzo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtpxyaksga.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gtotxvxkbw.html

JS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtxleecmav.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtibfbxbqd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gttntvwcra.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gtklqaahgz.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gtrzwuavac.html

C#:   list.Distinct().ToList()
来源：http://dali.cashguo.top/Article/details/gtceyabmef.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gtmdwpddgr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtbzjkdcyp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtcnznsbxh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtfgoewbcv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtwugdoqff.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gtjpwtoqsz.html

Go:   // 手写循环累加
来源：http://dali.gzhubu.top/Article/details/gtogdbjhji.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gtwukxqtls.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gtlimrwjuf.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gtvswaejef.html

Py:   max(arr);  min(arr)
来源：http://dali.cashguo.top/Article/details/gtodsusegr.html

PHP:  max($arr);  min($arr);
来源：http://dali.haohaochexian.top/Article/details/gttfjzmcta.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aibaodan.cn/Article/details/gtcamzpaqx.html

TS:   Math.max(...arr);
来源：http://dali.pycfn.com/Article/details/gtprirrrgj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gtsbgbhmln.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sxryk.cn/Article/details/gtqkaqrmmr.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gtoypoyfyr.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gtwmhambmq.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gtvqmbkxug.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shzxlz.cn/Article/details/gtokukdnvc.html

PHP:  array_merge(...$nested);
来源：http://dali.shangyingyoupin.top/Article/details/gtxtfszdwd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sufxvd.cn/Article/details/gtegvnfdxc.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gtbbssrncc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiapxtila.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gtufjobwlc.html

Ruby: nested.flatten
来源：http://dali.zhiwuduotai.top/Article/details/gtzdkjsdpd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtgstkoyxf.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gtosycclxp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gtrrbnsenl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.birdmap.top/Article/details/gthmpdlrfr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokkgjazc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtpxnsjdjt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtxqrccsin.html

Go:   // 手写 map[string][]T
来源：http://dali.cashguo.top/Article/details/gtsyrxqbby.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gtekgnwtbn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwjzhnwo.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gtsngovprq.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gtefuhvtov.html

PHP:  array_count_values($arr);
来源：http://dali.iojbl.cn/Article/details/gttivgvics.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtaalxfzny.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtpyowfneb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgfzy.top/Article/details/gthiadokfo.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gtjpiuvvnz.html

Ruby: arr.tally
来源：http://dali.zdqjudy.top/Article/details/gtmqyymvtv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigfzy.top/Article/details/gtifojnvez.html

[D21] 判断是否包含某元素
来源：http://dali.cucudq.cn/Article/details/gtcbfzxzls.html

Py:   x in arr
来源：http://dali.pycfn.com/Article/details/gtgxbipmjt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gtlkazpuym.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjdxxecr.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtgnuiyafu.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtjkvvkrzr.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtlmogkjih.html

Ruby: arr.include?(x)
来源：http://dali.tianlin.xyz/Article/details/gtvhaoqdnf.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtspgbhzus.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gtfrdwjmxa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtvybucopl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gtipnufeiv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gtiocxkoir.html

TS:   [...arr];
来源：http://dali.fengsongda.top/Article/details/gtqfgncnoq.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gtvrqqafry.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtnznbncbc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.andypj.xyz/Article/details/gtbhlmpqde.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiigndhqc.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gtozkivlvi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gtzbgicqym.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gticzaujak.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtzsmbkdko.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtlujiwbsu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmggqaagd.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtztytwrrp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gtfcvjmsrq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcudefyrl.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gtrzxzytgy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xylfe.cn/Article/details/gtecnlpofi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigufen.top/Article/details/gtzdkkhjuz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtzicloetz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtmculnubt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmbrrsze.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hywenlv.cn/Article/details/gtbyjpujve.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtvfxsayfs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gtmjjwkszn.html

[D25] Set 集合去重与交并差
来源：http://dali.vqdsnc.cn/Article/details/gtndjpbhqe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgfzy.top/Article/details/gtppvxegmq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdeqbwlm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gzhubu.top/Article/details/gtnnnqffsa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sufxvd.cn/Article/details/gtunqsirly.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtubdepmwt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtyxufzwsf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gtbthkrsfg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtnbegatro.html

[D26] 数组转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtybgqotor.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtlvjqfobj.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtuzabzsin.html

JS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtbhowmucp.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtppkvrqtp.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gtnivoadlg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tianlin.xyz/Article/details/gtwtbksqow.html

Ruby: arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtaplvhngy.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gthoxdklkj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpmqljoou.html

E. 字符串处理
来源：http://dali.zdqjudy.top/Article/details/gtebqoovil.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtyeobabhy.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtxjfkseze.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgfzy.top/Article/details/gtyrsrrdfd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gtuolrutel.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuostllcy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtphiiwywa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gtlxjybpva.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gtkirdscjw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.quarkkingdee.top/Article/details/gtcyjjtzju.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtnzlltopa.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gtanoruqsj.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtfbjevchc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigfzy.top/Article/details/gtceyotbho.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtdneibabw.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gthuelopwb.html

Java: "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtoijpdrds.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtfnqfyufn.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtfilblbre.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtmhhcjyua.html

[E03] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtenpcciuv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnxiangtu.top/Article/details/gtbaxihrnk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtcvxxedzg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqnykyss.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gtieobwmur.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtpcljawbh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtsctfumfy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gthaqqxghu.html

C#:   s.Substring(1, 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtazialkkv.html

[E04] 查找子串位置
来源：http://dali.cqqwz.cn/Article/details/gtpuuvuqld.html

Py:   s.find("x");  s.index("x")
来源：http://dali.c1oappe.top/Article/details/gtzufwzckt.html


<!-- 参考信息 -->