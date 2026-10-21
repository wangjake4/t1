代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gtaijtuusj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvqtcuqss.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangdashe.top/Article/details/gtrvkddjhr.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtuarbznnq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gtpatbogcm.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gtfonwfadc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zycfv.cn/Article/details/gtkvwcozpy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgsmjyly.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtancwebko.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvrgadkpa.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtgergauqp.html

Go:   // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtxsysptnv.html

Ruby: a, b = pair
来源：http://dali.quarkkingdee.top/Article/details/gtqvbocpko.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gtgwjlbstk.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gtgtomulio.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsmdcdtj.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gtspcrwrxq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gzhubu.top/Article/details/gtdmhqfumg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daxiang520.top/Article/details/gtlwkpfbod.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gtmmdzvueq.html

Go:   // 无重载：用不同函数名
来源：http://dali.yonumen.top/Article/details/gtinnhvzuj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jianghu66.top/Article/details/gtnbmtidav.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtjbtcvlnc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtetemhyhq.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtzlvwpvmm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbosfcxgi.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gtrxtvfitm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hysaishi.cn/Article/details/gtfiljidqg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.birdmap.top/Article/details/gtbiuldjtk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ydzc1.top/Article/details/gtbvwhhnjv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gtzzuwtfzn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gtisnmactu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnxiangtu.top/Article/details/gtagdfjbei.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gtokebvlmx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gtrkakgnao.html

[D02] 追加元素到末尾
来源：http://dali.sufxvd.cn/Article/details/gtcoflrupk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gtinwjfcdr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacqbsinb.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gthrhapomd.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtsdwhfmyb.html

Java: list.add(4);
来源：http://dali.pycfn.com/Article/details/gtskayfrbq.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gtahckfmdt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.bjfxy.top/Article/details/gtrwrintbh.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gtdnsuunpy.html

[D03] 在指定位置插入元素
来源：http://dali.zhoulong.xyz/Article/details/gtiphvpfkp.html

Py:   arr.insert(0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtakvgcgpq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hammf.cn/Article/details/gtyhmauhwm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gthfxwanvu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gtbgykfvsf.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtfhhmyagc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gtqmrkdzbe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gtvrxjthjn.html

C#:   list.Insert(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtkjlqdxwr.html

[D04] 删除元素
来源：http://dali.yuxming.cn/Article/details/gtgbfjcbia.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shuidangran.top/Article/details/gtzegmsgtd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shuidangran.top/Article/details/gtnwcfjzjb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gtfzwnyvdu.html

TS:   arr.splice(0, 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtlrmzwkuh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.redwolf501.top/Article/details/gtwzuammfi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.bjfxy.top/Article/details/gtexicxcrx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmxcyquj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gtsqwjudjt.html

[D05] 访问与修改元素
来源：http://dali.guannengcc.top/Article/details/gtiowkyovt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtohxdhxtv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gtwjstjrcf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtyfcybfjf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gtrntwumph.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ybcxt.top/Article/details/gtilxyhfmk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtxjlryvvn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtyqxebkeo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtblsrrivq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtrcirficg.html

Py:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtcxkmfsyc.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtxzoagbvs.html

JS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtrwfvucmd.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gthdlzppij.html

Java: list.size();
来源：http://dali.gotoacloud.top/Article/details/gtcmugqggt.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtklolqidh.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gtzkwgdqyv.html

C#:   list.Count;
来源：http://dali.cheryme.top/Article/details/gtxwfunrfe.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gtsrbzbvad.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gtnxczzqhg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtrurzquxq.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtxcspgnee.html

TS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtsnguwcac.html

Java: list.subList(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtetofcruf.html

Go:   arr[1:4]
来源：http://dali.daxiang520.top/Article/details/gtlbahyrvm.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gtuitwsjzx.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtsximbbuw.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gtegzkbbkv.html

Py:   a + b;  a.extend(b)
来源：http://dali.sysykeji.top/Article/details/gtckeseoon.html

PHP:  array_merge($a, $b);
来源：http://dali.sweek.top/Article/details/gtvaiwbmpi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gtuwmnxipz.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gtnqfdaopo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtugbbffol.html

Go:   append(a, b...)
来源：http://dali.yvedp.cn/Article/details/gtgqdgkroo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.9152youxi.cn/Article/details/gtohnpnrph.html

C#:   a.Concat(b).ToList()
来源：http://dali.iojbl.cn/Article/details/gtalcjyqdz.html

[D09] 排序（升序）
来源：http://dali.xuanzx.com/Article/details/gtsqjnvoqs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gtzusjubri.html

PHP:  sort($arr);
来源：http://dali.ydzc1.top/Article/details/gtcdnrpryb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sweek.top/Article/details/gtaoqbbbfo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shzxlz.cn/Article/details/gtwhotnpjb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.iojbl.cn/Article/details/gtxjtzcfgu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtsxwewmoe.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtcqftlwck.html

C#:   list.Sort();
来源：http://dali.bjfxy.top/Article/details/gtdnfuvfyj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shangyingyoupin.top/Article/details/gtbedortkj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guannengcc.top/Article/details/gtidbanfqh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gtsnyxbsol.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtivbflgja.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtubqtsdmn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gtdwnhrfev.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yueranfly.top/Article/details/gtsrlkeidd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhiwuduotai.top/Article/details/gtvjlxydnj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gtuhtwlroo.html

[D11] 反转数组
来源：http://dali.ydzc1.top/Article/details/gtgnomwloi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tianlin.xyz/Article/details/gtckrjxbsn.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gtnxyijsuq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cqqwz.cn/Article/details/gtuexnacam.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtisuvkodo.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtnzwdufss.html

Go:   slices.Reverse(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtxlnjmkbz.html

Ruby: arr.reverse
来源：http://dali.daria6918.cn/Article/details/gtrzshnugh.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gtcftquwga.html

[D12] 查找元素下标
来源：http://dali.redwolf501.top/Article/details/gtogfrwibl.html

Py:   arr.index(x);  x in arr
来源：http://dali.jlsjyb.cn/Article/details/gthalzfund.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtbqtkkyzx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtufnmgiqh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtiuzbnfjc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gtjpmwuvjn.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtjazynoop.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gtrtzceorm.html

C#:   list.IndexOf(x);
来源：http://dali.gogol.net.cn/Article/details/gtlmqhxdym.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nwbrower.top/Article/details/gtdcqvxrbj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dianchejie.cn/Article/details/gtbbsrycin.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ivvv.top/Article/details/gtrwqjafyy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtzqikuzdc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtgmmvbjpu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.9152youxi.cn/Article/details/gtnrgjjpvx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ybcxt.top/Article/details/gtibnguuzj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdptzfkf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cheryme.top/Article/details/gtpzfvuusd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gteanwcglz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedmzpkwg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258888.top/Article/details/gtcwubtlvu.html

JS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtwjopwzlw.html

TS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtkqzqofcj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nwbrower.top/Article/details/gtbfyfkmqv.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtbymdqxpc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daxiang520.top/Article/details/gtxllayvas.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gtuvlkxjvp.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gtixuafijg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gtxnoplher.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gtmrwyvtkm.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gthcyudamo.html

TS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtzepzlgnl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gtlbbrbbgp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gtpnnlkxlw.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtenhnmgrm.html

C#:   list.Distinct().ToList()
来源：http://dali.cucudq.cn/Article/details/gtwbxzspav.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gtmzsyxvhw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sysykeji.top/Article/details/gtgqtpzdgh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtrpjnffud.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtdfwkhkas.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtglvgrxue.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gtwjklmosv.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gtxicpjzwp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gttccnkosk.html

C#:   list.Sum();  list.Average()
来源：http://dali.pycfn.com/Article/details/gtcsayitxz.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gtkcytwewc.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtnolfhiaa.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gtzvldwzxv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gtkbnqpeov.html

TS:   Math.max(...arr);
来源：http://dali.chenlongwang.top/Article/details/gtiaagyfjz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gtcswmmzbq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtfzlnzofx.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gtcxdzwuca.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgsfcgus.html

[D18] 扁平化嵌套数组
来源：http://dali.gaohongyu789.top/Article/details/gtxjevihzs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gtkrgoilpt.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gthwpxjbrn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gtcztjuqwc.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gtvndcndio.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gtlzcqstdg.html

Go:   // 手写双层循环
来源：http://dali.yuanzhike.top/Article/details/gtrubgmyqw.html

Ruby: nested.flatten
来源：http://dali.pycfn.com/Article/details/gtlhyeieap.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gtaufavsae.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gtbxgrohni.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvacfeyio.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ivvv.top/Article/details/gtkokdgwds.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gtypgjgalz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yueranfly.top/Article/details/gtrilxbegc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gtnuyhmdov.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gtebkduecp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gtlojqoulz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.birdmap.top/Article/details/gtzjlrcprz.html

[D20] 统计每个元素出现次数
来源：http://dali.aizwys.cn/Article/details/gttzqjtifo.html

Py:   Counter(arr)
来源：http://dali.yueranfly.top/Article/details/gtbqbjlnjv.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtvquoxmsg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gttybpnlfa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gttqrjfdry.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtjrfnfxwi.html

Go:   // 手写 map[T]int
来源：http://dali.iojbl.cn/Article/details/gtewxoqmbm.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gtxurmigcf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gttjxzytse.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gtsojnmyrh.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gthhjckrwa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gtrfzpafkp.html

JS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtxthybcns.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtgtxidbpg.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtptjvctxs.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtntvobuui.html

Ruby: arr.include?(x)
来源：http://dali.ydzc1.top/Article/details/gtyeuzbklc.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtrllqzlzt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gtvomykfzn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gthblinnal.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdfjrxfc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gtinbibgdz.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gtzbyffnjs.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtudwvwugc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shuidangran.top/Article/details/gtooknlkiq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.vqdsnc.cn/Article/details/gtzdzewsqv.html

C#:   new List<int>(list);
来源：http://dali.chenzaomai.com/Article/details/gtecjhqakv.html

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gtdqzbecrr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuanzhike.top/Article/details/gtcjlhkwje.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gtywvtcaab.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtffktaexa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gttkjhtlqp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yueranfly.top/Article/details/gtnlcqdldi.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtuqncystt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gtvgbquvtr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fzhhl.top/Article/details/gtunnjwrdm.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigfzy.top/Article/details/gtdpeulukr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.9152youxi.cn/Article/details/gtginjjcvm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gtaybdrsaq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gtwkwdnmxy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtfojxovmw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pycfn.com/Article/details/gtgrvhevbo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gtxphcxhti.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gtoxpjoftk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gtgwbsfpsj.html

[D25] Set 集合去重与交并差
来源：http://dali.guowangkeji.top/Article/details/gtzonmcxtu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gtfghtitqi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gtudprphcc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pycfn.com/Article/details/gtwzlxrxpm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gthzgwospb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gtaprhdoso.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gtjfcksryb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gtvrhzbyus.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtihipmxmm.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtryvrdhfi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xinyue.icu/Article/details/gtdyhlpiwv.html

PHP:  implode(", ", $arr);
来源：http://dali.ydzc1.top/Article/details/gtpcotquda.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gthrtlzowi.html

TS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtucorxsxx.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtnkevyhyk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhoulong.xyz/Article/details/gtvhlbyayn.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gttbheuyoz.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gthijowhql.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtlgtaaboj.html

E. 字符串处理
来源：http://dali.c1oappe.top/Article/details/gtzxnmdwzx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtcekyrack.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjptyjyuz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gthbeqdcli.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.haohaochexian.top/Article/details/gtujmndutk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gtihsgdlrl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtsxlimahr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtecodtxmc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhoulong.xyz/Article/details/gtfhqknwkz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gtrbuwfloo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtpfbebgxm.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gtxxlqedfo.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtmtnbecbe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlafknqoq.html

JS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtrhoiwdhd.html

TS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtgryoxtdz.html

Java: "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtyxpbsvip.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gtenxylswe.html

Ruby: "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtnezwwmcp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.andypj.xyz/Article/details/gtxqxhmfrj.html

[E03] 截取子串
来源：http://dali.daxiang520.top/Article/details/gthndpxvnk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gtisycvsjb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtrhzzdjal.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtqmqwufxb.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gtdqzhkdco.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtfdkqjhsy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtfrxchewg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuanzx.com/Article/details/gtqswrwqqr.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gtqqzxjhfa.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gteytfbeln.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtcdydqkpz.html

PHP:  strpos($s, "x");
来源：http://dali.gogol.net.cn/Article/details/gtqgadtxrf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gtarujlpzr.html

TS:   s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtraxhzexb.html

Java: s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtxwdgispv.html

Go:   strings.Index(s, "x")
来源：http://dali.aibaodan.cn/Article/details/gtdqukxjsc.html

Ruby: s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtpxvdhtyq.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtrrpbuyfe.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gttbgtgroy.html


<!-- 参考信息 -->