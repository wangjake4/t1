代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbfnyaryd.html

Go:   func add(a, b int) int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsfticxd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gtbdtejwzy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gtjixwbxgf.html

[C14] 泛型函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjprhfjb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daria6918.cn/Article/details/gtagewzjde.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtyktjrwzu.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtmsuebjcm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gtyvwcdtwr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hywenlv.cn/Article/details/gtvcjffzot.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daxiang520.top/Article/details/gtqsqkfmgf.html

Ruby: # 无泛型
来源：http://dali.ehwqpu.com/Article/details/gttmzxpefy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gtyqutlxnm.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gtzabpbqfc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gtvxrulqed.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gtlnvitqkw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gtsmjsygqp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gtsruocowp.html

Java: // 无解构
来源：http://dali.xylfe.cn/Article/details/gtpwzwyxij.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtgzwvapqz.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gtflhiafjn.html

C#:   var (a, b) = pair;
来源：http://dali.zycfv.cn/Article/details/gtvketiwvu.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gtrhitpkcn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gtptwexjfp.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gtauvlyafj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxuanxn.top/Article/details/gtkbfmgkui.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gtvwuldryk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ehwqpu.com/Article/details/gtgwdylxtg.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258.top/Article/details/gtzqlqgbor.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxinkj.top/Article/details/gtovfbbuxf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.birdmap.top/Article/details/gtvkwqjhmj.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtruudvsth.html

D. 数组 / 列表 / 集合
来源：http://dali.meibo888.top/Article/details/gtycbtzblo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtuvyzbzoz.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gtzwhicbzj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgfzy.top/Article/details/gtyxcmmhbz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cucudq.cn/Article/details/gtoepmpefq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jyoumei.cn/Article/details/gtbiijsmtx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigfzy.top/Article/details/gtdkcgoqyb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pycfn.com/Article/details/gttchlvaub.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zycfv.cn/Article/details/gtoxxghtmo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtpiwltatv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daria6918.cn/Article/details/gttnhjgvwm.html

[D02] 追加元素到末尾
来源：http://dali.ivvv.top/Article/details/gtybxhsbjw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gtlbwfmhoe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yueranfly.top/Article/details/gttdvgjcsj.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtrwebymxi.html

TS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtsxatmzyu.html

Java: list.add(4);
来源：http://dali.xziqi.cn/Article/details/gtcicztcae.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gtxbzbbpzy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gtxnlvztlp.html

C#:   list.Add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtkyoaxwza.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gthtpqljjt.html

Py:   arr.insert(0, 0)
来源：http://dali.fengsongda.top/Article/details/gtpsjrtfmv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hywenlv.cn/Article/details/gtfrivhsdj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yangfankeji.com/Article/details/gtctxkerhc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gtlqvnipsu.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtrgvrnynu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aizwys.cn/Article/details/gtuwiojaew.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxuanxn.top/Article/details/gttaslsmqb.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtlphegfum.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpxzddpg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtplauexjj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gtuuhaagfh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gtzeamweea.html

TS:   arr.splice(0, 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdxvpimy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jiagoushi.top/Article/details/gtkdwedvev.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gtojswiyyd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.iojbl.cn/Article/details/gtxjmtjpkw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.bjfxy.top/Article/details/gtsvsaufqh.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gtrruuokfa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtnzxvajif.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtlqnspyrt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtcqcbmmgj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxwvkyey.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gtxeosjqod.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjbunrea.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtymrpwwvi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtthdurcco.html

[D06] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gtybhehtup.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtvydowdiu.html

PHP:  count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtekxjyxau.html

JS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtiedzdkik.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtioxsjved.html

Java: list.size();
来源：http://dali.sufxvd.cn/Article/details/gtvikprqhm.html

Go:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtdhpovfcz.html

Ruby: arr.length; arr.size
来源：http://dali.0kj1m.cn/Article/details/gtgdmxryar.html

C#:   list.Count;
来源：http://dali.yanxiufei.cn/Article/details/gtffezkzhn.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gtfzbunjpk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangtech.top/Article/details/gtiecvtjul.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gtbqiqsjat.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtaeujanjr.html

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbdtomhi.html

Java: list.subList(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtwfhzscfu.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gtlenkjmhl.html

Ruby: arr[1, 3]
来源：http://dali.gogol.net.cn/Article/details/gtmoijgjaj.html

C#:   list.GetRange(1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtmajsfskx.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gtmrdugial.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijhugksk.html

PHP:  array_merge($a, $b);
来源：http://dali.hnxiangtu.top/Article/details/gtxkcnbutz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pycfn.com/Article/details/gttkgsxgiz.html

TS:   [...a, ...b];
来源：http://dali.haohaochexian.top/Article/details/gtiwpekoaa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cucudq.cn/Article/details/gtkihebann.html

Go:   append(a, b...)
来源：http://dali.0kj1m.cn/Article/details/gtsqqpahrr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yanxiufei.cn/Article/details/gtccscjtqu.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxzqzrdy.html

[D09] 排序（升序）
来源：http://dali.shzxlz.cn/Article/details/gtdypirzlr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtvjyiovls.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtgtceuvbp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gtuzvpmjws.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gtjeybguls.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.vqdsnc.cn/Article/details/gtetpkmein.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoonxpyes.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtdwyiqgww.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gtdwpxzqfy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gtrnsbarfg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xylfe.cn/Article/details/gtijyuyvhu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gtcnkbpjme.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtmbynjmmi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtenuumoze.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gttxgfqhdj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gtbpwiemhn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnqzz.top/Article/details/gtzlfryhwo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sxryk.cn/Article/details/gtjrexzpvd.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gtrmwmoecl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.quarkkingdee.top/Article/details/gtrmmqeqlt.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gterfmitnx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gtzwycbfff.html

TS:   [...arr].reverse();
来源：http://dali.cheryme.top/Article/details/gtzscykrmh.html

Java: Collections.reverse(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrvdqdxq.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanabpgiz.html

Ruby: arr.reverse
来源：http://dali.ehwqpu.com/Article/details/gtugavyydn.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gtwdmvhkjl.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gtuoyuwnzx.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gthfmldcxh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtjakymmpb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gtbxjogkcv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gtjuiqegcf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.redwolf501.top/Article/details/gtdqoimlgg.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtekmkfsdv.html

Ruby: arr.index(x)
来源：http://dali.nanxuanxn.top/Article/details/gtshknfdij.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtpnryottv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gtjdtgmqtz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jiagoushi.top/Article/details/gtorccgyse.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tian-w.cn/Article/details/gtjpemhcen.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtdhxxukbj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtffabxyay.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtusnhabdg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gtbkatfyuc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfrgyrps.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.316326.xyz/Article/details/gtalkjisdr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gtvsxnjxal.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ppjwa.cn/Article/details/gttiqnooxv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yueranfly.top/Article/details/gtznpqxgsm.html

JS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gtsdrglusa.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtnvzeuspr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gtfzxzvzqr.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtydzvklec.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtxrsqhlxd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gthnuyqmob.html

[D15] 去重
来源：http://dali.ehwqpu.com/Article/details/gtbawcxiqd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtwbxqhxxx.html

PHP:  array_unique($arr);
来源：http://dali.smart0.xyz/Article/details/gtxyphsxbb.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtjglomxhr.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgougzig.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gtmzfiwegd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhiwuduotai.top/Article/details/gtkbvbmztl.html

Ruby: arr.uniq
来源：http://dali.nanxinkj.top/Article/details/gtzerihucf.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtsyzzqosg.html

[D16] 求和与平均值
来源：http://dali.andypj.xyz/Article/details/gtxqzsjger.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtaijqrahm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.havefunace.top/Article/details/gtweuhpekj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtstrftwgn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtjhwyfivl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.0kj1m.cn/Article/details/gtiyfzwnkm.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gtajnxepfb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangdashe.top/Article/details/gttfgvyeni.html

C#:   list.Sum();  list.Average()
来源：http://dali.havefunace.top/Article/details/gtduslodhw.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftgxueqy.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtzvnfkyxy.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gtopitsach.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhoulong.xyz/Article/details/gttarizebv.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gtrfcuzofu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.316326.xyz/Article/details/gtjlljbfgn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gtgybuzdmv.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gtsmynzlma.html

C#:   list.Max();  list.Min()
来源：http://dali.c1oappe.top/Article/details/gtmrmjuwjt.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gtjbalfbku.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gtrnofbknw.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gtchmncpdn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cucudq.cn/Article/details/gtlnuwmmka.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gtiaqcvdlg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gtosysgneb.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gtikqiflvv.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gtwpyftjrn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ivvv.top/Article/details/gtdkjttmfs.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gttnnidbzb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gtnvlkepgy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.quarkkingdee.top/Article/details/gtgjxmmwtb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gtoyrbbhqx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gtkqxwwmeu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gtzsopymud.html

Go:   // 手写 map[string][]T
来源：http://dali.ybcxt.top/Article/details/gtsqasrdfm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gtjczpkogg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gtqawqnskj.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gtmhwlgqld.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gtfufbcgif.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gtjuznvyyk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtkpkvdtcy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gtrtzsowsf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gtbnaftdyp.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgwusqew.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gtqwmxrqwr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzgvgqwo.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtxaeeqsac.html

Py:   x in arr
来源：http://dali.ydzc1.top/Article/details/gtgusccfhw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtahlwncbd.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtkortfvwe.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtqqofetpi.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtuvxqdgyt.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtyenqvihr.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtsrnbncvt.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtnuilmtuz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.redwolf501.top/Article/details/gtwtlcqwdo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gtqatrewbd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gthwndfets.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xziqi.cn/Article/details/gtzgfoecnc.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gtmvkrfjqw.html

Java: new ArrayList<>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtekynztnu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gthkigqjel.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gtzitipoeu.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gtqtuvxuwg.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gtemlxzqah.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hammf.cn/Article/details/gtshuyhpxl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gtllynhuen.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtmmpejrlr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtcdcpmcvw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gttoihsqcr.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtvgrmdrsk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gogol.net.cn/Article/details/gtrdpghuss.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gtzpfgbdmo.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gtjsttclzu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.kuanghao11.cn/Article/details/gtepanntvo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gtmsbaqqaw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aibaodan.cn/Article/details/gtkaiescvh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtgswrebnk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtjhvdjalp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.bjfxy.top/Article/details/gtehihhrmv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gthjyyoecc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gtavrloqsr.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gtwbbhydqr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jyoumei.cn/Article/details/gtsulenulw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgdrqhha.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pycfn.com/Article/details/gtamplbkgq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gtbnlippxp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gtoboadapb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guannengcc.top/Article/details/gtdracbjix.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxuanxn.top/Article/details/gtvpjzhxnd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtfcgwrgtd.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gtyczatwmz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtvdpfcxxv.html

PHP:  implode(", ", $arr);
来源：http://dali.gogol.net.cn/Article/details/gtnyrqhizj.html

JS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtkbtqzihc.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtltofiiby.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtskbetpjr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gaohongyu789.top/Article/details/gteeeyqexw.html

Ruby: arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtkbeqgsql.html

C#:   string.Join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtjjdjephs.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gttelfzbis.html

E. 字符串处理
来源：http://dali.zhengqikj.top/Article/details/gtoqelargi.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgqyrlywb.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtislzerve.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gtlcjmalls.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gtgbpukhuf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtxrahuaow.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gtwvsmrmjm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gtekwihfod.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gtjylkmkbj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gtznybjwai.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtypgcdsce.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gtzbshgcpl.html

Py:   "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gthtrhosor.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gtbfhsmejn.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtjrgyujez.html

TS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtcqhfmtll.html

Java: "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtotouwbxu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnxiangtu.top/Article/details/gtsrpjuwrk.html

Ruby: "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gtgnvuayqn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gtliqwjjsw.html

[E03] 截取子串
来源：http://dali.pycfn.com/Article/details/gtouxckpff.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gtfbcjzhpf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtabderavw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gtxziotmoj.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtskcwtqsm.html

Java: s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtqvlstarr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gtkgsxgpcv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gtztcksbbb.html

C#:   s.Substring(1, 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtibnozmnd.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gtwnjhxkhe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cucudq.cn/Article/details/gtbiaadtpk.html


<!-- 参考信息 -->