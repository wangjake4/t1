代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gt2plvmyjho.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2splinkox.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gt2drcbuudx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gt2hwlgyhul.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gt2xonvkyxx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vptjufgm.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gt2tgofqvrt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gt2nkmfuwvh.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gt2esxdukuc.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktolpcdh.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2aayuatog.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cdnleiting.top/Article/details/gt2zawcqubq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gt2vmrmexlu.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gt2hbbnkipg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jicwkgpw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2lhhelzfv.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gt2jispqhri.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2hptxjqre.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gt2eiwfigom.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhixingplan.top/Article/details/gt2ucwoetwx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvskpgnl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2kkwlglxx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2qlhhqdfq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gt2evpowbbb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gt2mzfufkwx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gt2nkdpuygx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gt2ykpbdlmx.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gt2usoamnil.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gt2epkgqcbj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2ztjnbodd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2vyxozmfw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgzrgbmr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2oecxplmq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gt2jdrcwhly.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vglwzhrk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2wuvlxgcm.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gt2eezyhgbm.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gt2tnkheybl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2nlzyvzuy.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjwinold.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2fkrcevzz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2skvcikjc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjjigggw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gt2ewamlqzc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2kiatrpqr.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpncmsnt.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gt2uvunydzj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gt2bjgrbkuc.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gt2zfcwfohr.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypadkknl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gt2yyfkejdj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gt2snlbkxvf.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytktrhyf.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gt2lamswlsa.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gt2rmuxarzy.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2sbizatrm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gt2mctztuyv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2bcxexlwq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gt2wsrwqhfq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixvbavxc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gt2ockodciw.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gt2spcyqqgj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrampsrz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gt2umjgihao.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gt2hlksfllo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2xynhtuso.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gt2dvkgkhpv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2memuygeg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gt2vncennfk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gt2lsjpquka.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gt2fvpeuzbo.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gt2ibunwnlp.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2raswroey.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xylfe.cn/Article/details/gt2mjcjblfc.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2dbuxrxvn.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2zytcywvv.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2synqnink.html

Java: assert x > 0 : "必须为正";
来源：http://dali.iojbl.cn/Article/details/gt2kxcdbjde.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hammf.cn/Article/details/gt2bsyjlaxj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gt2bpkhfavt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2pnzwkvyu.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gt2viaumfee.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gt2hsyogbys.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gt2hpezwofn.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gt2frjlaufo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gt2tgfyqjrw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gt2qwottfhl.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gt2kezanhht.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2acjtwyox.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gt2pczgisdc.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gt2vwjwqwlw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smrwollr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gt2runptcer.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenzaomai.com/Article/details/gt2bcujztjy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gt2uovtpskq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gt2axduvpks.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.kuanghao11.cn/Article/details/gt2rbqkmqsn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gt2dwcntlmo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gt2zodasyvd.html

[H10] 资源自动释放
来源：http://dali.gaohongyu789.top/Article/details/gt2tucxnmjb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gt2fhpzfhsb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gt2jxgpobaj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2kesmypii.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrwjbybq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zdqjudy.top/Article/details/gt2rlccyvcy.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gt2zzhgpuqf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gt2djxtjihm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2ohqmxzvi.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2pcdebbox.html

I. 正则表达式
来源：http://dali.316326.xyz/Article/details/gt2maxadtsn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2chpjhciy.html

[I01] 判断是否匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2sdzmwkhx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gt2pwpwxsow.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2unkxoumt.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gt2nzjksnwz.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2hfnrxxcp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gt2ygywmsic.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2psymmnsy.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gt2fztdlick.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gt2pvrpjxfk.html

[I02] 提取所有匹配
来源：http://dali.tianlin.xyz/Article/details/gt2wmcmlobz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2wunmffgh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenzaomai.com/Article/details/gt2lgfutdtr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gt2ywpzsovg.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gt2kpmavgmm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gt2cbfkaaec.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gt2xhmmpaup.html

Ruby: s.scan(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gt2rufdzput.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqwxhyyl.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gt2pzgfedqv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cllohomc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gt2gxksxshv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptwjwheo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fzhhl.top/Article/details/gt2ppkcqdvl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gt2cishdoqx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gt2cwbgjgxw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gt2mazbymgt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gt2ljtnafse.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gt2zqrfcwar.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.smart0.xyz/Article/details/gt2fwuazfks.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gt2jvtwqjmn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2tfmdkeru.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gt2aggkukvu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gt2abxwligz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2euxzgfkr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2ukdydmrz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2ysnruxev.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gt2thyquzpg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gt2mfmnsucj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2vaolbben.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2mvwilsia.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2facowjys.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gt2nekxvxuu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rjenbqsp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2dqfedqif.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gt2bzylgbsf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gt2otueeeqw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ersoprxj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gt2mavayueg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gt2ysozejqu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayrkaugu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.316326.xyz/Article/details/gt2hkpmktgg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangdashe.top/Article/details/gt2mpkqhltr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gt2tnygyscf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hulwjqmc.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gt2zibmhwcn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpgkkaov.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2kenvmvwr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gt2xbmawwlb.html

TS:   /error/gim
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnhxwzuw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogotvzqy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.c1oappe.top/Article/details/gt2eaiagjno.html

Ruby: s.scan(/error/i)
来源：http://dali.zdqjudy.top/Article/details/gt2lcuatqxz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvysoeiy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ydzc1.top/Article/details/gt2xxnfrdig.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gt2zsobbdcd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2pffecnfz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2sbwraogf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2nxcrhuoi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gt2cqkkqsxs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnxiangtu.top/Article/details/gt2dlooybkh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mewytfwr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbipjjzs.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2nfoureit.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gt2ulymklmq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2xwhvfckt.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gt2ymyorfjz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gt2bgajceyy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gt2egvrrump.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gt2mvvvwmcg.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gt2emhpflfi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gt2nkygimdt.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gt2fcyespof.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gt2ighsyanu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gt2wiqsnkme.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gt2sxyomkjl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gt2xsptuivh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gt2wbljipad.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gt2midlaief.html

TS:   d.toISOString()
来源：http://dali.cucudq.cn/Article/details/gt2iyikwlsd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gt2ruxwodhd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gt2omjbdkgv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gt2xzshswhq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gt2zteyistu.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwqjbzhb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guowangkeji.top/Article/details/gt2qmpcmhhk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gt2zvwuwnxf.html

JS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2ylvcieor.html

TS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2jymsjavm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2ihxuaehu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2qttxjknq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2gjgzcbxf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gt2xpvezvud.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gt2vpmayzjj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2safhfcwt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gt2ayiplxyg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gt2qgkbqnpd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhoulong.xyz/Article/details/gt2glvincec.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2spwtlikk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dkpollzk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gt2hynuzscn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gt2yphhqvwo.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gt2krvwelzw.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gt2ffdklcmu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gt2udlokxno.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gt2tguenamq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gt2mozplzls.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2gmzzyelj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gt2gfvuluth.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gt2giwxkjgu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2zarmsuqg.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gt2phowwwnu.html

Py:   (end - start).total_seconds()
来源：http://dali.mhx1999.top/Article/details/gt2hkpnxpek.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gt2ilczlneb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gt2zzjhiaxf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gt2uhcoayzz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gt2aopxjdre.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbegyhxr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gt2vqlnbaam.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gt2ipveiyla.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gt2kbkpsvud.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2lsgqnlvc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhoulong.xyz/Article/details/gt2dvrplhvm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2jfzzfgzq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwbpctru.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2xcqahcda.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2sndmquhk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2ikryamzu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2tvnmirve.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gt2eolomjke.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gt2hjzpqude.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gt2qdzwtrcl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gt2xeexjlpw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gt2ekfyonuz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gt2efoqmrgc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gt2pdpfiunq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gt2faotyvct.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gt2fhtborfe.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gt2ljlbukxs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gt2fxkgmsgp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gt2urwhkwnw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gt2rmcvuohh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2xkqkotkw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gt2lumrhwcs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gt2fopopyqf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gt2qcuqtyns.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gt2jpvleasy.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gt2dafvzosn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gt2zzdaddvx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ggrfkuzi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2dpgbxyyi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gt2xstifpps.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gt2ogfbqjkw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxjwqrup.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gt2kzlugpiv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ockwubrj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2rtjaylmo.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gt2ajpvzaxy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2zrpayogh.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2zeefpqbt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gt2pmcuymsx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gt2almlogtq.html

JS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gt2wyensfum.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmksjowv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.svipenyu.cn/Article/details/gt2tvrizneq.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gt2arkozjld.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cucudq.cn/Article/details/gt2lmdngmbp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gt2crhzhzeq.html

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gt2yztxvfci.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjeunwax.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gt2ycummemv.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2aglzuxcy.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2kkbsmuic.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2edficodb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gt2qpvmalkz.html

Ruby: JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2zksagsad.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gt2qhneezct.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gt2gpynespj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gt2xfuuvres.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2efbjxiyy.html


<!-- 参考信息 -->