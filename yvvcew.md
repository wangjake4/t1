代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gtyahxsocw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtqrjochvj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gotoacloud.top/Article/details/gtzrvpqsbr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtpcncvntz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gthwbylnru.html

Go:   func add(a, b int) int
来源：http://dali.jqgfzy.top/Article/details/gtdpvscwgb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gtyhslrpqi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gtsunhegmf.html

[C14] 泛型函数
来源：http://dali.c1oappe.top/Article/details/gtzqrilwde.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gtiqdyjtsk.html

PHP:  // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtilihfnhu.html

JS:   // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtshgokvin.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cqqwz.cn/Article/details/gtavtkxqyr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gtexurzabw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dianchejie.cn/Article/details/gtrupxrvcx.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtvjitwgkq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtkzoatuxh.html

[C15] 解构 / 展开参数
来源：http://dali.ehwqpu.com/Article/details/gtxftfcxbb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sweek.top/Article/details/gtdzysuycf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hammf.cn/Article/details/gthxsglzoe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfgwxuno.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuanzhike.top/Article/details/gterbsopfx.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gtlotdesyp.html

Go:   // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtrjcqhfbm.html

Ruby: a, b = pair
来源：http://dali.316326.xyz/Article/details/gtdbanznif.html

C#:   var (a, b) = pair;
来源：http://dali.aizwys.cn/Article/details/gtuyxglkpz.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gtcyokdmzu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gtbavxvfds.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gtygtqtdnm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj202588.top/Article/details/gtdvmdhbpu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj202588.top/Article/details/gtbdxbayum.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gtqmyqixwl.html

Go:   // 无重载：用不同函数名
来源：http://dali.meibo888.top/Article/details/gtykdxknke.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gtkfffodht.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yonumen.top/Article/details/gtveqyjwse.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gticcifgyx.html

D. 数组 / 列表 / 集合
来源：http://dali.pycfn.com/Article/details/gtvvjvyfhe.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqivrtedy.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gtozpypirx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ppjwa.cn/Article/details/gtgrofxklg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gtchyzayny.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aibaodan.cn/Article/details/gtimecpfcl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gteulnaqir.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dianchejie.cn/Article/details/gtplyjveti.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gttvjzgmsl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuanzhike.top/Article/details/gtnmfkjhoo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gtaumeelul.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gtahfptlxk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yongpay.top/Article/details/gtmuksthca.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gthgwjpvdg.html

JS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gtgjeewbmp.html

TS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gtvwuojqzv.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gtwvyfyxmb.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtvyzvmzsi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gteermlozh.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gtyhnwzfnz.html

[D03] 在指定位置插入元素
来源：http://dali.yuanzhike.top/Article/details/gtretyorrp.html

Py:   arr.insert(0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtgqlstwys.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gtxytqxkku.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sufxvd.cn/Article/details/gtxaooolbs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtvqapvqfw.html

Java: list.add(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtcckggouy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtmzevahdz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hywenlv.cn/Article/details/gtinrzjrmh.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtthvmimpm.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtnvmrgnza.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfomvowx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gtxkeokavt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenlongwang.top/Article/details/gtmyrkijwz.html

TS:   arr.splice(0, 1);
来源：http://dali.jyoumei.cn/Article/details/gtxoawmsaw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shzxlz.cn/Article/details/gtcjclyqdr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gtlgmxejui.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gtuncxiuya.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gtslkhwysr.html

[D05] 访问与修改元素
来源：http://dali.mhx1999.top/Article/details/gtyojuvjsb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtdjzkvfex.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtdxhdxaxp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtcochvduj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hywenlv.cn/Article/details/gtmqmzglnk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gtmfqckuay.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtftsykpuy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtrxfsguxl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtxvysgzdl.html

[D06] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtpopbkhsv.html

Py:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtebcyokiw.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtbcbxsedm.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtcnonqn.html

TS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gtbnuisifa.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlltseqbk.html

Go:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtnrnwuhjo.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gtbachnrsn.html

C#:   list.Count;
来源：http://dali.xuetiantiany.cn/Article/details/gtcplzksfa.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gtghdegugq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gtgfkaoeso.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gtaqwdkpuq.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtksweorcn.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtoeitrgru.html

Java: list.subList(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gthdgtgxrq.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gtzpsjfser.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtsnhdlmhw.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gticjstfri.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gtbzouhktk.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnthgmait.html

PHP:  array_merge($a, $b);
来源：http://dali.jlsjyb.cn/Article/details/gtyklyhqcy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gtsbftignj.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawhenufn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmnmjrfh.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtjvnnuavt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppsawcva.html

C#:   a.Concat(b).ToList()
来源：http://dali.sysykeji.top/Article/details/gtuvwjkxid.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gtdwotwgbn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtgxvufyjo.html

PHP:  sort($arr);
来源：http://dali.mhx1999.top/Article/details/gtxyzlxnmx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.birdmap.top/Article/details/gtpwdoxsqo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.haohaochexian.top/Article/details/gtzhltomgn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fengsongda.top/Article/details/gtdkcvydle.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtvqnjoqdg.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gtmiwwbham.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gtevrocuve.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gtrkfpqwwf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gtiqtkwqqq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gtjojzqlcb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtxisgcngg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtvfnosikh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtranftain.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daxiang520.top/Article/details/gteaegrqfa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ivvv.top/Article/details/gtsfacgszy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guowangkeji.top/Article/details/gtyjqmkskm.html

[D11] 反转数组
来源：http://dali.zycfv.cn/Article/details/gtyauhxioj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gttwkshqox.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gtpxwrdpbs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuetiantiany.cn/Article/details/gtqmewlnse.html

TS:   [...arr].reverse();
来源：http://dali.zhengqikj.top/Article/details/gtlzzwmvpk.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gtyeagvhxr.html

Go:   slices.Reverse(arr)
来源：http://dali.yonumen.top/Article/details/gtxfedtpin.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtetbltldr.html

C#:   list.Reverse();
来源：http://dali.316326.xyz/Article/details/gtxzgdypri.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gtaorvioks.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtrnaavyaj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtsboqzsys.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtnpoxrewz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtrxpmsjlb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxinkj.top/Article/details/gtmkablyfr.html

Go:   slices.Index(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gticrqyudk.html

Ruby: arr.index(x)
来源：http://dali.zycfv.cn/Article/details/gtustzscta.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gtwjvaxfdo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gtaeqvffzp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtktqzdskw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gtqqivxokj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gttxaclmxv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtxdfjkejz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtphrjmcxv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daria6918.cn/Article/details/gteovsedco.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jyoumei.cn/Article/details/gtyjnmiuec.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtvlqtpnnv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.meibo888.top/Article/details/gtcyepqtcw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtgtytipwr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtvjotenzf.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtsruhwxbp.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtamczcxmd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuanzhike.top/Article/details/gtggqbppel.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtmkfksjap.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtzicraamp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtrppvsppy.html

[D15] 去重
来源：http://dali.aizwys.cn/Article/details/gtgftmtlzl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gtazjbjkmk.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gthusgkgkz.html

JS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtzrzeryhw.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtoiwccdve.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gtcbovfgcy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.vqdsnc.cn/Article/details/gtpncnhniv.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gtelxedmlj.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gttgrrpxzu.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gtgnapulmr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtngwvyylq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ydzc1.top/Article/details/gtzgnrzgiu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gtumeyalnr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtiojgiyar.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gtpcwizjgc.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gtrjntuyvz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gtwaxcfwah.html

C#:   list.Sum();  list.Average()
来源：http://dali.tian-w.cn/Article/details/gttoleoads.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gtpjkzadbj.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtgqohwdas.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gtbmrreqam.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgfzy.top/Article/details/gtxlgaefis.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gtbjyetsrw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gtnjmdnuxe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gtpvlxnqvx.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gtxjbllpyc.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gtmyutiljp.html

[D18] 扁平化嵌套数组
来源：http://dali.snrcjt.cn/Article/details/gtvxdtragf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gtywjmgnod.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gtucecdkwf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gtfyobiqxs.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gtccqxntqy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gtrrroqckb.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtgbfvnzhr.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtuuerepru.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtnddotgru.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gtfoolihju.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtamooxmwk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xziqi.cn/Article/details/gtaxyjjdwe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gtzgxflsvj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtbnqyxqzt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yanxiufei.cn/Article/details/gtohcygjfj.html

Go:   // 手写 map[string][]T
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmlzhqxb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtopluiink.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gtnricdrbc.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtauxejljn.html

Py:   Counter(arr)
来源：http://dali.birdmap.top/Article/details/gtqgbmrmge.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gtfleiwcoo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtlyhvdwsd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtndxseuqx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlmutlds.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gtcqcagfym.html

Ruby: arr.tally
来源：http://dali.haohaochexian.top/Article/details/gtutxrqmfk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gtmbtmcnpd.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gtwodreicc.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtirrwfzcy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shuidangran.top/Article/details/gtjckvjjwq.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtwwivticz.html

TS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtsrqswfls.html

Java: list.contains(x)
来源：http://dali.gzhubu.top/Article/details/gtzfjqdsaj.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtihhpsorx.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtwmddbnvb.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtsppmgcsl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.smart0.xyz/Article/details/gtoaqzzhji.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gttlhxgyor.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gtygxsetyj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sufxvd.cn/Article/details/gtjwwsvcqb.html

TS:   [...arr];
来源：http://dali.jinqigfzy.top/Article/details/gttkxwidiu.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtkwwwgvfl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xinyue.icu/Article/details/gtlnssfemc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnxiangtu.top/Article/details/gtzhtbiemi.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gtzzhcyjna.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsiqjnrgr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtjpebwxor.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gtgedsqzvk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtvkyjihbv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtmnhudwpd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gtdvrkfiqf.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gtjlmoqtua.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xinyue.icu/Article/details/gtbmwjcmug.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shzxlz.cn/Article/details/gtjwnbdcto.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gtlewgvefm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gtacuepyuq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gtuolqougf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtaswarelp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtcthnjack.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqudjwri.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gttiuiwzre.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gtciogfyyv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pengpengdd.cyou/Article/details/gtgvlktgea.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gtekqfxxqb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jiagoushi.top/Article/details/gtvygtdvke.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gtrsakqiyk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gtxliopowt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gzhubu.top/Article/details/gtirbbiwyv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gttcurvstw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gtjiqighnz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gtqhgxndjl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gtmrlsslps.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gtjlzenjnz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtidxbjbly.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtskrfaphk.html

JS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtrpcoeaan.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtmfyslltn.html

Java: String.join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtyzobuhgt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gtalxwwkqg.html

Ruby: arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtnwflvpzi.html

C#:   string.Join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtgvxdtmzd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtplskukfq.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gtcqrqczvb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxdmyiejo.html

[E01] 拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtydfyxyun.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigfzy.top/Article/details/gtejmtatyd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gtydrkyyrb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokexixbj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gterzflfbd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gttgzcdjrj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gtlemopofz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gtvdtdomvx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj202588.top/Article/details/gtkfklmzls.html

[E02] 重复字符串
来源：http://dali.yueranfly.top/Article/details/gtquwlaptw.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtwyhxkpmj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guowangkeji.top/Article/details/gtafribuce.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtzixuenqs.html

TS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtmtphqftf.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtnmbzzvjf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenlongwang.top/Article/details/gtjlncnrhz.html

Ruby: "ab" * 3
来源：http://dali.cheryme.top/Article/details/gtcxbuurce.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gtgignrnri.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtltieldth.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkajvxfk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtthfxfxkd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrtmrehk.html

TS:   s.slice(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtpqpoziom.html

Java: s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtjgioybbb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ivvv.top/Article/details/gtuviwwigu.html


<!-- 参考信息 -->