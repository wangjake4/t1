代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtvyfpbgec.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gtbgwmnmve.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtezuhdgsy.html

Go:   // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtlfcbbhsi.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gttvtilbwk.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gtkvwkvopi.html

[C16] 函数 / 方法重载
来源：http://dali.cdnleiting.top/Article/details/gtmxdugttq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gogol.net.cn/Article/details/gttnxyybtc.html

PHP:  // 无重载
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqutylddg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gtenuehxvm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjjugids.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gtwlbpglzm.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenlongwang.top/Article/details/gthtlidxfg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.andypj.xyz/Article/details/gtgbdsbraw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtsydllcrt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtigjrwmjx.html

D. 数组 / 列表 / 集合
来源：http://dali.ybcxt.top/Article/details/gthihpcvnj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtytzeseee.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigufen.top/Article/details/gtjazvgcvx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjrvnpbd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.havefunace.top/Article/details/gtisqwjbjg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gtdgigivuu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtsdwuhv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypibixto.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gtotlgwogc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cucudq.cn/Article/details/gtayevbuxm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sufxvd.cn/Article/details/gtdcbzppat.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gtuievikqk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aizwys.cn/Article/details/gtshlgvvnd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gthkewjlpa.html

JS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtassnxeil.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtafpfvukb.html

Java: list.add(4);
来源：http://dali.yj20258.top/Article/details/gtsaeypiim.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtixatiyuz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.0kj1m.cn/Article/details/gtkkdmdnne.html

C#:   list.Add(4);
来源：http://dali.ydzc1.top/Article/details/gtrwibcjhn.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gtswfxbfcp.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gtmbptkjra.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gtatwyuyvq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sweek.top/Article/details/gtluaiwcqh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbncryzx.html

Java: list.add(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtfcykpkmb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hywenlv.cn/Article/details/gtdossqgyq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gogol.net.cn/Article/details/gtuschplqi.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdahhouhm.html

[D04] 删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmezxasq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yonumen.top/Article/details/gtfrttskdk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtsysbnxvt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkhsiywl.html

TS:   arr.splice(0, 1);
来源：http://dali.kuanghao11.cn/Article/details/gtgocdfino.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gttbpxzwwl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtnipzkfbm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gtmjlpuixw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgfzy.top/Article/details/gtbphfsuhu.html

[D05] 访问与修改元素
来源：http://dali.jianghu66.top/Article/details/gtgemyejvs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtgnnspbmv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gteohshpsd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtuzhcvpkc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gtqgcgbgnv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gtwczzwxlc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtipcvwzas.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtqeeqpmsz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtiimsqjnv.html

[D06] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtxfslaflp.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtfvfwncet.html

PHP:  count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtzlnmaxua.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecxuhaxk.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtbshotuat.html

Java: list.size();
来源：http://dali.ydzc1.top/Article/details/gtqjhgkvxu.html

Go:   len(arr)
来源：http://dali.316326.xyz/Article/details/gtgeifnkau.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gtzvcqfrgn.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gtrdiyrfeo.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtvgxanobp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gtpgdevbsh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtvhopcgpp.html

JS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gtumsamxed.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtfvebygmq.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtfioiychb.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkscsfkuh.html

Ruby: arr[1, 3]
来源：http://dali.yongpay.top/Article/details/gtjqgohjgb.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtcjtoodmq.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gtqapawkzz.html

Py:   a + b;  a.extend(b)
来源：http://dali.tianlin.xyz/Article/details/gtgbbxtolh.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyfbovka.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gtlsqgluxk.html

TS:   [...a, ...b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyzkuryq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258888.top/Article/details/gtafablhub.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gtdjxvbivq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtfkltqdjb.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gtlucashkf.html

[D09] 排序（升序）
来源：http://dali.jinqigufen.top/Article/details/gtsejeppqc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtwwbyorrh.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gtilctioas.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.0kj1m.cn/Article/details/gtjltoizvr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yanxiufei.cn/Article/details/gtvmjcoswe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.smart0.xyz/Article/details/gtllblkhaz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtlcoctalr.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gtjpclowyb.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gtdmfoksvv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigufen.top/Article/details/gtnwdmfucs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gtykukohxa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gtjeswneix.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtoxhekgkt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrulztaee.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pycfn.com/Article/details/gtkyqjmyxz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gtjbwjdbnq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gtqmjqzntz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yangfankeji.com/Article/details/gtlpcdjlno.html

[D11] 反转数组
来源：http://dali.hongshengwenyu.top/Article/details/gtohkmzqun.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gtrgyffntm.html

PHP:  array_reverse($arr);
来源：http://dali.tianlin.xyz/Article/details/gtsapewlpk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gtvuoysweb.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gtixakknri.html

Java: Collections.reverse(list);
来源：http://dali.9152youxi.cn/Article/details/gtaasglxny.html

Go:   slices.Reverse(arr)
来源：http://dali.cheryme.top/Article/details/gtiyjphabo.html

Ruby: arr.reverse
来源：http://dali.0kj1m.cn/Article/details/gtguvkgpvc.html

C#:   list.Reverse();
来源：http://dali.0kj1m.cn/Article/details/gtodwohtys.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpngnhewa.html

Py:   arr.index(x);  x in arr
来源：http://dali.shzxlz.cn/Article/details/gtnlsgzryf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pycfn.com/Article/details/gtwwmzozji.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuthwlacs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gttdnyhdtj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gtpfuxrhlj.html

Go:   slices.Index(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtotaemyin.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gtvznzsxzt.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtonkuelys.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhixingplan.top/Article/details/gtvrahfoaq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guowangkeji.top/Article/details/gtehraroaw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xziqi.cn/Article/details/gtybarohkn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtywjnfnnd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtgirtqhbk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gtrjwandzm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gtdvwfrwpv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtkwuuzehy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlggnwagj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtlznwexjk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fengsongda.top/Article/details/gtlptwcfby.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gtdxkrwjbk.html

JS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gttjpkxunf.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtqlrjhyhj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gtbgzxkqti.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gticifjaox.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtmhcgvsox.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtgjdmuzgc.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gtlwjqbbqi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtepjybzhf.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gtzvbtmqtt.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtwlialjqa.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtymwmiatd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gthtzbwlpy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gtkytuyser.html

Ruby: arr.uniq
来源：http://dali.gzhubu.top/Article/details/gtbikhjxnb.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gthblsujqr.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gtpenajnlw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtqrvzpuvi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gtsfrrikxu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gtgusaqloa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gthenjketi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gtvnmgpwjw.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfpfiabr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gtcsegyzrp.html

C#:   list.Sum();  list.Average()
来源：http://dali.yanxiufei.cn/Article/details/gttfqadwnq.html

[D17] 最大值与最小值
来源：http://dali.aibaodan.cn/Article/details/gtuuxeremm.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtlpqtsjef.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gtfyrmxlus.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gtjginefen.html

TS:   Math.max(...arr);
来源：http://dali.hfpthk.cn/Article/details/gtcbidjcoa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ppjwa.cn/Article/details/gtlqtaveyu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gtauqdrksh.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gtkfseyive.html

C#:   list.Max();  list.Min()
来源：http://dali.jlsjyb.cn/Article/details/gttpvqlyes.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gtlxtsumei.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gthjsrctxi.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsveinsef.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenlongwang.top/Article/details/gtoibwpmjg.html

TS:   nested.flat();
来源：http://dali.yongpay.top/Article/details/gtcdtxciax.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.haohaochexian.top/Article/details/gtogckiccz.html

Go:   // 手写双层循环
来源：http://dali.cashguo.top/Article/details/gtpafdcjcl.html

Ruby: nested.flatten
来源：http://dali.fzhhl.top/Article/details/gtunknojje.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gtcghrdrxj.html

[D19] 按字段分组
来源：http://dali.xziqi.cn/Article/details/gtqwtmuaoh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.andypj.xyz/Article/details/gtpzsszyte.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gttwbyjbba.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gtyxplhfwe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gtlddleamp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jianghu66.top/Article/details/gtegwxxhhs.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gtsdhjswqs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gtdiltemth.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gtduzhqdgl.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gtgrfaqjrj.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gtacltxgst.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtobsljviq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gtqlqrskhu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtuhzojxup.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dianchejie.cn/Article/details/gtnzsueysb.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gtwliotuvd.html

Ruby: arr.tally
来源：http://dali.jlsjyb.cn/Article/details/gtllwolewl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuetiantiany.cn/Article/details/gtfmjnxdsj.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gtlrznclrg.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtqaxabvry.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gtvjslzuej.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtlgrkxumi.html

TS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gteuozbpis.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtxzmlqbgt.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtjjieshye.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtxqgjyvpb.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtkhcvikdf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shzxlz.cn/Article/details/gthlxwojig.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gtvcztjqso.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gthxdcuhxj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gtzkbvtgvy.html

TS:   [...arr];
来源：http://dali.zhiwuduotai.top/Article/details/gtzjfxhxhg.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigfzy.top/Article/details/gtejzncorb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yongpay.top/Article/details/gtnqifxmzc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gtvdolovbk.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gtdskhgyth.html

[D23] reduce 累积计算
来源：http://dali.dianchejie.cn/Article/details/gtkhdpqrle.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtpxdqjwnv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtivjdrmac.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtntwrlzgj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtqfyavvtp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gthyhpnvwq.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gteswanrcc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yueranfly.top/Article/details/gtynzkdbsr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.svipenyu.cn/Article/details/gtxdggilys.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gtipckxkwb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sweek.top/Article/details/gtmhxnfuaq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gtpwrssxvq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gtpvwdiyoe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtsseqpzno.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gtajipvdfj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gtoijqichm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258888.top/Article/details/gtwxnpdbwr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gtodxuvnge.html

[D25] Set 集合去重与交并差
来源：http://dali.xuetiantiany.cn/Article/details/gtenmzyhsx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jianghu66.top/Article/details/gtcgeqddte.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtlynhtlay.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gtnwsdvamt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ybcxt.top/Article/details/gtxftyjgsg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtwugjqzit.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gtlrzbaakf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gtgvgpvaar.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gtynhfcyit.html

[D26] 数组转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtxkwflyau.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfvusfba.html

PHP:  implode(", ", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtzzueddim.html

JS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtnwsxkyhd.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtjyucpavb.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtovkcuqlk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gtwpfxeukp.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtlwbemekj.html

C#:   string.Join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gttpqdlqxl.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gteaurchdi.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gtzlkdwlfy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtsvavnsvf.html

[E01] 拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtxljjehed.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigufen.top/Article/details/gtmepipcrj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daxiang520.top/Article/details/gtbdtsogio.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtfvtusyqw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtqxyqjhjy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aizwys.cn/Article/details/gtndsxptmi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtovmoptbc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gtapstepme.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtpytakehq.html

[E02] 重复字符串
来源：http://dali.shuidangran.top/Article/details/gtbutahvgw.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtqmamkcuu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gtvibdmhmh.html

JS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtkicqgene.html

TS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtqnnpzceq.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtysazgotc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gtiqwrohwd.html

Ruby: "ab" * 3
来源：http://dali.yonumen.top/Article/details/gthyervhtp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gthhgxyfub.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtucllhpbb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuetiantiany.cn/Article/details/gtafrmdqfw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtesyflzyz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfdjxutk.html

TS:   s.slice(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtoxsdcrii.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtrquxkztk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtmwkkmknx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.havefunace.top/Article/details/gtdjbhauas.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gthftogfha.html

[E04] 查找子串位置
来源：http://dali.yongpay.top/Article/details/gttzhrcqlj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtkvetszwl.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gtalfjikku.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gtlzqcmlux.html

TS:   s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gthxbnnxau.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtgmtjanih.html

Go:   strings.Index(s, "x")
来源：http://dali.snrcjt.cn/Article/details/gtdzkevnii.html

Ruby: s.index("x")
来源：http://dali.daria6918.cn/Article/details/gtvfifbuvu.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrkbghbo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.kuanghao11.cn/Article/details/gtoacfxidi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gzhubu.top/Article/details/gtdtixdpnp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gtmvfzvoje.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtbevflsji.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gtzosnthwh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gturoaszpi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhengqikj.top/Article/details/gtasuxwdix.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gaohongyu789.top/Article/details/gtufecosle.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtwvytpufk.html


<!-- 参考信息 -->