代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gt2proiuvyt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gt2ivzlijpg.html

Java: // 无解构
来源：http://dali.yangfankeji.com/Article/details/gt2hivysuvy.html

Go:   // 无解构
来源：http://dali.yongpay.top/Article/details/gt2rvioqtfo.html

Ruby: a, b = pair
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nrkpcnmk.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gt2blmesxyv.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gt2icddlxzs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gt2cctsddqh.html

PHP:  // 无重载
来源：http://dali.zhengqikj.top/Article/details/gt2dktcgnvf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ydzc1.top/Article/details/gt2jaqobtje.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zflrhrdb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tanke756.top/Article/details/gt2sopjmpdm.html

Go:   // 无重载：用不同函数名
来源：http://dali.fengsongda.top/Article/details/gt2evbrfuvf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.haohaochexian.top/Article/details/gt2llhfgvfp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gt2zbsiwrfg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2hzniwpwd.html

D. 数组 / 列表 / 集合
来源：http://dali.vqdsnc.cn/Article/details/gt2ujivfcyv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2zvztxqrk.html

[D01] 创建数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gt2cdxzylny.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gt2ajztccbh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gt2rvbqupzh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gt2mmfmhmtt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jiagoushi.top/Article/details/gt2fyjwtcoq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daxiang520.top/Article/details/gt2ppikzsoh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gt2dbidftaf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.meibo888.top/Article/details/gt2sxfkepuj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gt2tcydlkqt.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gt2rwuzqxgw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gt2vrymlkha.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhwampdt.html

JS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gt2etwabycz.html

TS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gt2kpbiwlra.html

Java: list.add(4);
来源：http://dali.yuanzhike.top/Article/details/gt2ihhtjvkq.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2rhovsaqk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gt2ftyxyqch.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gt2kptrkjfl.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gt2hylmywnw.html

Py:   arr.insert(0, 0)
来源：http://dali.nwbrower.top/Article/details/gt2tfrgiejj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gt2ufazcbej.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cucudq.cn/Article/details/gt2rwdvqbcf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gqbglpfa.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2pzwnhejn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gt2ujfpisrs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xinyue.icu/Article/details/gt2olfardmw.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2rfqfrsxk.html

[D04] 删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxytomqw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gt2btuckfpo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gt2flnemxqi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zycfv.cn/Article/details/gt2kexsmkjp.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gt2fpjchcmf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvudrwwd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gt2vxqsqhfz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gt2egbwttjg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gt2irzldaxd.html

[D05] 访问与修改元素
来源：http://dali.yangfankeji.com/Article/details/gt2bmrsftst.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gt2xjqxgtqs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gt2anpijdyu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gt2rsyijfgt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gt2spbopbfg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gt2omjtwqtm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gt2mueqdkmm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2fvrwjfqx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gt2woegxgir.html

[D06] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gt2kzsanemw.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2fycbcngj.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gt2hrelfxtz.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gt2nocixxwb.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gt2zxdgifzx.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwiwouoa.html

Go:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2xgwzvyml.html

Ruby: arr.length; arr.size
来源：http://dali.jqgufenzy.top/Article/details/gt2zinqjtpf.html

C#:   list.Count;
来源：http://dali.kuanghao11.cn/Article/details/gt2zlqsnpos.html

[D07] 切片 / 取子数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbzsgosv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guowangkeji.top/Article/details/gt2qmlosefu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2yvgoiqdi.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2hmzmirwl.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2anunyoae.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2gufymmqt.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gt2yhwqljnv.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gt2brrjrrtv.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gt2gyjdpvyz.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gt2pxwprchj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uunmeuxp.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gt2imixweri.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gt2iialetri.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gt2amesvlpe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2qcmpuncu.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gt2jcrrzsdq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2uprjehyk.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2cusbkowe.html

[D09] 排序（升序）
来源：http://dali.gotoacloud.top/Article/details/gt2dzxedkdf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gt2lstntuun.html

PHP:  sort($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2sjpgpaew.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gt2eobsjvgd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yangfankeji.com/Article/details/gt2femjyjpw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cheryme.top/Article/details/gt2qflapfpc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2thtkljhw.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gt2iakisikw.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gt2dcyaqhso.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2musmpfrv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmhsrklo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gt2fltoszbe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gt2tfxrmnrb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gt2vlyevaoe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gt2avanysvi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xinyue.icu/Article/details/gt2eyhoxesn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yueranfly.top/Article/details/gt2vodomdcr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.svipenyu.cn/Article/details/gt2karxirsu.html

[D11] 反转数组
来源：http://dali.ydzc1.top/Article/details/gt2ctmcwtzv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gt2pdryotzk.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gt2zanrawcb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tianlin.xyz/Article/details/gt2jvxkpltw.html

TS:   [...arr].reverse();
来源：http://dali.chenzaomai.com/Article/details/gt2krvqxbnf.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbmfoqfd.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gt2gygdkrjo.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2utxlejgy.html

C#:   list.Reverse();
来源：http://dali.9152youxi.cn/Article/details/gt2ikcxsujw.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gt2mwogpeua.html

Py:   arr.index(x);  x in arr
来源：http://dali.snrcjt.cn/Article/details/gt2qlmxovjr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gt2tzzwlkhs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2pmryobsp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gt2abmkgrnh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.smart0.xyz/Article/details/gt2xpgcahgd.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2kqpzcoxp.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xgieavxy.html

C#:   list.IndexOf(x);
来源：http://dali.chenzaomai.com/Article/details/gt2zgtoadwv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgfzy.top/Article/details/gt2gabdwawk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2lqvujply.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sufxvd.cn/Article/details/gt2obvuokfx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2sgejftht.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2bdwzqyfp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2hxjxsahs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jlsjyb.cn/Article/details/gt2pwhqvhdc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvdnmdl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2tpmiklmf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gt2idskdgff.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gt2irliqctx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ivvv.top/Article/details/gt2hbdfrirn.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2clzepecs.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gt2bmzmmics.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbbjwhsi.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gt2mjsbwjeh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gt2rbjzndci.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2wlolaanu.html

[D15] 去重
来源：http://dali.316326.xyz/Article/details/gt2fcyziyse.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gt2nsvsdomu.html

PHP:  array_unique($arr);
来源：http://dali.tian-w.cn/Article/details/gt2dngozvfu.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2osksqzql.html

TS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gt2zcoixceh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gt2fkdozedk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gt2kevdtats.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gt2uiwjgkms.html

C#:   list.Distinct().ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2agxdblkh.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqbhuhg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jijvnkzx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2hxreyhag.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvtzqerq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2wdykcsyz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gt2anvmajgj.html

Go:   // 手写循环累加
来源：http://dali.hammf.cn/Article/details/gt2ougjxuxi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.mhx1999.top/Article/details/gt2lxwsvzrb.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuxming.cn/Article/details/gt2uisppqrp.html

[D17] 最大值与最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsjpyuuw.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gt2tnuersuc.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2nbaclxno.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gt2letugvrf.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gt2bqivjiln.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uyejohrm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2ladzclsy.html

Ruby: arr.max;  arr.min
来源：http://dali.nwbrower.top/Article/details/gt2orwzbwjt.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gt2skvxgpyg.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gt2aswtvmae.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gt2lijqsmuk.html

PHP:  array_merge(...$nested);
来源：http://dali.tanke756.top/Article/details/gt2pfpkruls.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gt2dbymhtum.html

TS:   nested.flat();
来源：http://dali.yj20258.top/Article/details/gt2geuajmjs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gt2xstwiduq.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gt2tmnnhaxh.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gt2muwaabjf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjkyzhmd.html

[D19] 按字段分组
来源：http://dali.chenlongwang.top/Article/details/gt2bybgctex.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wczcepko.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gt2wkijewch.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqdugdtq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gt2usqizjsv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gt2euphrvci.html

Go:   // 手写 map[string][]T
来源：http://dali.cheryme.top/Article/details/gt2nvwukjrs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.vqdsnc.cn/Article/details/gt2tpkqmedh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nwbrower.top/Article/details/gt2trlkfdit.html

[D20] 统计每个元素出现次数
来源：http://dali.yanxiufei.cn/Article/details/gt2yfebfann.html

Py:   Counter(arr)
来源：http://dali.yonumen.top/Article/details/gt2bchwbmsn.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dljhukpx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqtdqcwr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gt2vulcidbr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gt2vqtewxji.html

Go:   // 手写 map[T]int
来源：http://dali.quarkkingdee.top/Article/details/gt2keeweuws.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gt2iufwbotr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uninurvq.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2nylhdybg.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gt2vnqknczl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdstlxzl.html

JS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gt2iigyvcdm.html

TS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gt2kcukhxie.html

Java: list.contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2afpqdnrx.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2cjenujtn.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gt2fxhencfk.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gt2ugezhrfv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gt2ihapkwtc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2qdtizjjq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gt2dqryaadz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gt2mxhrevkn.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gt2hxdxeyqg.html

Java: new ArrayList<>(list);
来源：http://dali.sysykeji.top/Article/details/gt2dgbwgmep.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yvedp.cn/Article/details/gt2rqwrdqiq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nwbrower.top/Article/details/gt2fxwbtfsa.html

C#:   new List<int>(list);
来源：http://dali.haohaochexian.top/Article/details/gt2yifomydj.html

[D23] reduce 累积计算
来源：http://dali.quarkkingdee.top/Article/details/gt2kiovdkfb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.meibo888.top/Article/details/gt2guhjlzyf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tanke756.top/Article/details/gt2yvwyglua.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gt2bbrzwwej.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gt2xvlfavet.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gt2ahkyegmw.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gt2tnjistsg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gt2uivbuyjl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kblpfvbu.html

[D24] 字典 / Map 基本操作
来源：http://dali.hywenlv.cn/Article/details/gt2giwhuhku.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gt2ijrbijyw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gt2jqgrfcff.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gt2dlllbmrl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gt2imtsgbof.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cnnxpqfm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gt2bskewpjj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gt2cyenqxxa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ltvuclan.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gt2dkghiiik.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gt2zepyqnjk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gt2kayesmuw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gt2qkujexwu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gt2snjuqojy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2scqjckpj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yueranfly.top/Article/details/gt2gcohrzaf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gt2axwtkyft.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xziqi.cn/Article/details/gt2qutunant.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtciuoqa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gt2tokeqhyz.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gt2tmyagicr.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2xvrxptds.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2pomuaxbv.html

Java: String.join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gt2xfrevtul.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gt2tsngedwa.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gt2rfrrcjpx.html

C#:   string.Join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gt2ejhhcuzh.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2zofopoxs.html

E. 字符串处理
来源：http://dali.iojbl.cn/Article/details/gt2tedzkzki.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2tnbxymon.html

[E01] 拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2dgrzhtif.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gt2znndjtgr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sysykeji.top/Article/details/gt2ttblopwh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gt2dkmlxome.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2vpxvebck.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gt2litcbcpp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2behncrhk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gt2exhsdhhz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2qzvkrugo.html

[E02] 重复字符串
来源：http://dali.guannengcc.top/Article/details/gt2pvcbjwlo.html

Py:   "ab" * 3
来源：http://dali.havefunace.top/Article/details/gt2pdmompax.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohkoisxd.html

JS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2siiazcwl.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2dyklwypv.html

Java: "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gt2jrhfaxzh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fengsongda.top/Article/details/gt2iojnsmye.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gt2emrggbqs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aizwys.cn/Article/details/gt2zaelyuuz.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nbitfxov.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gt2usbnbots.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gt2uzjieszb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2hpjwolko.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2ptuzebfb.html

Java: s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2ahtugtuk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gt2ehgqjfsl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fzhhl.top/Article/details/gt2nuqgzuhj.html

C#:   s.Substring(1, 3)
来源：http://dali.sxryk.cn/Article/details/gt2xdhyybhy.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gt2ouxjekhp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2puiiyyfd.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehhzqsfv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shzxlz.cn/Article/details/gt2scebxyhq.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2ttkxnnpf.html

Java: s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gt2bkdgfttj.html

Go:   strings.Index(s, "x")
来源：http://dali.hnxiangtu.top/Article/details/gt2upplkuem.html

Ruby: s.index("x")
来源：http://dali.guannengcc.top/Article/details/gt2abomvfun.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gt2ezsxpqiz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gt2vnulicos.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gt2sslzdpuy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gt2epapgpab.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2apfdnyll.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dianchejie.cn/Article/details/gt2fanwtwxy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eskoeqza.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tian-w.cn/Article/details/gt2txjasvkx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.havefunace.top/Article/details/gt2crinwtbd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2yjehvjym.html


<!-- 参考信息 -->