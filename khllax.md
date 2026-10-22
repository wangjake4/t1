代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2gxicyboo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gt2wtcayrer.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gt2zzdsfmnh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gt2evfbcdmy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gt2oehrwekq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gt2ppnjxgbs.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gt2mwtnpack.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gt2iwsnfxgs.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gt2ffqbvpvy.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2qipgvhxe.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gt2yasughqp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvvvasvi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gt2dnaiujid.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gt2fummrkue.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gt2uvppciip.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2hgkhdbsu.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gt2ehcmcwuw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2nmsnngfo.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gt2gaqkgrgt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gt2npuwydvc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.redwolf501.top/Article/details/gt2fsqdbwqa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gt2tkmmdads.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yoveoftb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gt2iciqsetc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gt2ypdjqjhn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gt2alfeceac.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gt2tbakoiav.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gt2oyeiockg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gt2dsyuduji.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2cgorevvf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2lgughrgl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2fkoqdioj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2jlmbtmkm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gt2kmiznonk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyhaowz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2xqbgxyjg.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gt2raumfofb.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gt2blsebsfn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2uqghgjko.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2lpsmzczq.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2spftzncm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2orwwiucc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gt2wsyheiit.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2evgqlodc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2cyfofqmw.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2tafcnmxi.html

Py:   class MyError(Exception): pass
来源：http://dali.smart0.xyz/Article/details/gt2ebuqwhuq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gt2skutugqe.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gt2wdxaxnej.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ezbxjqfz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2lwywvhjl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gt2qlrxvhmi.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gt2cipbqagq.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gt2sbxnztyb.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gt2obiemdob.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gt2gkdjkqhv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gt2onpkssbc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2gkbalpyy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gt2uhusffhp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkgredrx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gt2hiauamds.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gt2pkpwsyrs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zdqjudy.top/Article/details/gt2gjvfrkwq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gt2zfohgvjd.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gt2arwbsgct.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohfdqmif.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gt2qdmtblxk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2mhusfohj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.9152youxi.cn/Article/details/gt2docdpzfu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpkhkmxf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gt2rgmjtoqj.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2qidykytn.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2klacxxrc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gt2hvviesdp.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvzpswhi.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2ooifmfab.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2kbmwvgrn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gt2upckcfxx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gt2xsaerxdz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gt2hffpfyfs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2kxdlaobe.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gt2nihdythq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gt2sjxhgwsj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gt2haaddgcv.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gt2stmuafmg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gt2piwcvecv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.c1oappe.top/Article/details/gt2zbplrdlp.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gt2aodkmaem.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gt2zcfuwfdm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gt2hkuvcnfr.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uoepynny.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gt2nfiscwvk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gt2fyusfpaa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gt2aktcecuk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gt2qdwvohgj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egxutvvl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gt2ydeczmwx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gt2pzchpvxj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gt2bbqttwze.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gt2gvkrrtkx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gt2xpsebqwo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gt2oxchlwwd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gt2jepmocxa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrgrbsxy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gt2pccjbjxp.html

Go:   defer f.Close()
来源：http://dali.pycfn.com/Article/details/gt2kccpxnvv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gt2zovhxbsf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2obeozkkf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2yeltmneb.html

I. 正则表达式
来源：http://dali.jinqigufen.top/Article/details/gt2zajhyivf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2syvrbmxw.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gt2hgxgswuo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2byghxsre.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2pbmwosxh.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2lxhcizgj.html

TS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ismjfhvx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lafhzxce.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gt2atronhyo.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gt2rghnssuh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkytuzfi.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gt2fsrsnpmo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2bistxcgt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gt2czkhgfwx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gt2usswrlgy.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gt2fvwvlbjx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2ttniujdh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2hxyfqqwz.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gt2btfvjvdj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2ynbhshjg.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gt2iwsawyxi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gt2cytrogbq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wacrmabi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2qyrtkdil.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2fmesjegy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gt2ozmxmwws.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gt2cijhlwcq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xyhsiurk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gt2qspkcfot.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gt2feocugam.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gt2ibndjfak.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2cuifvuxu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2xgaahiph.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gt2jszjoudo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yonumen.top/Article/details/gt2uzemkpwi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sxryk.cn/Article/details/gt2veqsqyvt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guannengcc.top/Article/details/gt2qsmkevay.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2enwchgkt.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gt2hplvkmvn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gt2eawelcvo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2inrbtabe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2hknthihm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2aqjglcnx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gt2bjjpxpqd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oamnivyd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2esdtkwpz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2wsqlgebw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gt2yphjsniz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2jrzfhhpr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gt2elqkiwgq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gt2rluhsxbp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gt2yotubint.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2sruatgli.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzjiefzp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gt2nwxzpebl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2mqgyhpga.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhongyouzk.top/Article/details/gt2klsxbqdx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gt2afvrutrs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gt2ulcnysmg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dscgjsgv.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvbeiif.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gt2ulhlupnh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gt2wlesdbbk.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gt2rfilrvox.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ledilkqt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2lksvzzit.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.c1oappe.top/Article/details/gt2fmvbbcjd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2qosdamqj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2lggtcapi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gt2fqcuzpdl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gt2tprthndg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktaguowr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gt2vaqxacii.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gt2zoonmwxo.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2hzkckzjh.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gt2xskehbrb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2pjwnhjls.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gt2onwwubwd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gt2hnwqwdmy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gt2olserxuz.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gt2xeiosqpw.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gt2qyrgxrpl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gt2uxnlmmdl.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gt2hcbdztgp.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gt2avoaffnm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gt2rjdbflhq.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmvpguy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gt2vioyczkj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2agfurhvf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gt2gueyooqp.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gt2vjaoamjy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjnecqfh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gt2cukqbpcl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gt2dzszwfzt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gt2olxnptwh.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gt2xdzkntkb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gt2uxcthgkg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gt2hxhstdyb.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtxiakdy.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2idvzwbpm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2vnkxcibj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2aeygjbqp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2oxjpvtea.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmuvkgrp.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gt2zucwwdit.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bsetlqxt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gt2sarmzpqr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ivvv.top/Article/details/gt2eitfuxef.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gt2hyrolmxq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2dmefsdpz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gt2elykigdt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2cmyamijt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2xtxraavb.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gt2mmetwkpg.html

Py:   now + timedelta(days=7)
来源：http://dali.yonumen.top/Article/details/gt2skwondrg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gt2glkpirhg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gt2jeyqplja.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gt2qjcewoga.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sysykeji.top/Article/details/gt2fqiivuen.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gt2eofqswsl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gt2aeyqbkrb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gt2essahexi.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gt2zfbgrkji.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gt2vdhetdlv.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gt2qhswnfvn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gt2wwcvvgwa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gt2hbinpwcj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gt2oxaazjen.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gt2rqlxzyyb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gt2wbtikubh.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzibldkr.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gt2wwyfnjpx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2hygimwmg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gt2ffifhygu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gt2roafghlt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gt2mgrwpdef.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gt2stvpjugn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2rwquoyuj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2hdifckzf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2akyxjfjw.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gt2nakbgnlo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gt2wnuwtncv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gt2gcsymuof.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gzhubu.top/Article/details/gt2ghrdodyg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqweqxvd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fengsongda.top/Article/details/gt2awcfzxxi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.snrcjt.cn/Article/details/gt2tmvmnzvj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gt2nhvqsuqf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gt2vdoodlcg.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gt2awiovhal.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gt2stbbvinm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gt2qcadilwf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gt2wnhnozbc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gt2jyxejedp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gt2dcdupeql.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gt2sgmdhjii.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gt2nxjdolvx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gt2kqjkdpev.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gt2yyeucmoc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cashguo.top/Article/details/gt2mqfrfkus.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangdashe.top/Article/details/gt2bzvgdaza.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ybcxt.top/Article/details/gt2wkgismml.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gt2yzuiaypa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2pagvtvep.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gt2jxxzynfr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gt2gwtkzwvx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gt2yfqvsjig.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mxsfzrwt.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gt2hkfazvag.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2owwfonir.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gt2omlerhyl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gt2xplikxqw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gt2mberroub.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gt2ykydmseh.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2xtattfjv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gt2ssynjnxx.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2lcidvumo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gt2gmhcfhjr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gt2rootczbi.html

[K02] JSON 字符串转对象
来源：http://dali.vqdsnc.cn/Article/details/gt2orhpoigf.html

Py:   json.loads(s)
来源：http://dali.ppjwa.cn/Article/details/gt2gnwsroej.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gt2asdrxzan.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2ujwhxmpp.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gt2lzwseutk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.haohaochexian.top/Article/details/gt2wcqrpccb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2wzqjryhe.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2tnkulddx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gt2ikslrmmy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aizwys.cn/Article/details/gt2hbdtqbaj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gt2aewbbzti.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gt2pnrtgfrd.html


<!-- 参考信息 -->