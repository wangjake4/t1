代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gt2eanlvxir.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gt2aujslbnh.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gt2sedspwrq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gt2mrcebehb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gt2jewulgpk.html

Ruby: obj.instance_variables
来源：http://dali.vqdsnc.cn/Article/details/gt2irwwiwav.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2flcwplgv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2hrxinxvr.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gt2cuwicoao.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2hifgdtms.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gt2gqpygrjq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gt2fpbwvgbz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gt2zzmmxqpc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gt2kbybstce.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gt2iufakist.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gt2bfodeezu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gt2kpwwzasf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gt2dmekydjm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gt2bvsyaron.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gt2udlbuoqs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gt2xqefvjhx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2ycyiiuwd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2kkmjgyfa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2pisbtoys.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fbyiwdon.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gt2loqnffya.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gt2zpujtevq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2ttqxnigs.html

[H03] 主动抛出异常
来源：http://dali.fengsongda.top/Article/details/gt2uutdydtf.html

Py:   raise ValueError("错误信息")
来源：http://dali.shzxlz.cn/Article/details/gt2utxnlopm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2elsopybn.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2dtaqcqem.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opoyeaqo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2ttyxtddj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gt2apqxtkfw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gt2lydgjvcd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2vohbpiav.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gt2bxssxcvu.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gt2izsmsljn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2opondmuw.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2yygqhjiz.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2ohsohous.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2mxrtahrl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gt2bhykdhxl.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gt2hsmhesaw.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gt2rxnvddmf.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2ftlonnyq.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gt2jvlquzsg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkqifvzv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvievtua.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2iohpegmm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2taeqvvtz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tanke756.top/Article/details/gt2gwgwolay.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gt2glaqmygs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gt2pikqcsdv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gt2hoasqmnj.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gt2uuoglyab.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2tzviwfso.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gt2clpoezur.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2gsuyjrjw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gt2jcekzjhp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivzaktym.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gt2pzwonnnr.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gt2sfjobduk.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gt2njrwrfyg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gt2vfwkqwxz.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2mollarhw.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2xbqcpxvk.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2robctttk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gt2zhntnfzp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gt2agpywryl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gt2xynihrmw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfzjapwg.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gt2hicjaryz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tanke756.top/Article/details/gt2kjfpqhpz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gt2juejvqwo.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gt2oarbqggo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gt2sakiormm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gt2pxxpgjoa.html

Go:   err.Error()
来源：http://dali.jiagoushi.top/Article/details/gt2vnmfxeuk.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gt2xebpsbsr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fvhvivco.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gt2pxbircdz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gt2ojalkaqs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gt2ojtvqpcb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywtdztrd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cheryme.top/Article/details/gt2ebluabws.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guowangkeji.top/Article/details/gt2fudzhxqb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gt2pqtktghm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gt2blfmjyjc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gt2bjfmdujt.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gt2yfkhjilw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gt2blqboicz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gt2iigtmngw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2xmccuuvh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gt2zbgcxkcd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gt2tuptsbcb.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gt2peuooqkv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gt2fhnffces.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2eplathox.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2qwgzjecz.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gt2zndajxfo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2urnhkuav.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gt2puitridx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zaerzxyq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2stlvjgiy.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gt2muitmfyu.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gt2xvfxsnjn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gt2sbsnuhxs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gt2oycrcgxr.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2phdfuddf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yongpay.top/Article/details/gt2gyvacqce.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gt2dswcglga.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2puudgocg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxpjtqeu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gt2xicnqfgg.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgfzy.top/Article/details/gt2gsmwjpyn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2yuqyzlch.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gt2tnffecrj.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gt2bumqmeyd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2okegyivj.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gt2hzunhepe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tian-w.cn/Article/details/gt2dyzavnbu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gt2lgekpvfd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.bjfxy.top/Article/details/gt2ocfmlebi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gt2cdhvkagp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gt2kcmdzfpx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gt2qltwvafu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2srdlfjjv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gt2ikfyevdr.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gt2antqgwpk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pycfn.com/Article/details/gt2emhijfbl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2zswkxmos.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2ovspnxcy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gt2qphcycqb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gt2zowkwnki.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gt2fskecxve.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2ldbqhfun.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gt2tlgnupum.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gt2bhfmwruc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gt2luxezeul.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vppeghat.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdjjrnqh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2ebtliuxt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gt2prfqrhup.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2tziwcrdh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2mdbpidvf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gt2dsxrujxs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gt2pwajdkbv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2srcmfxmq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gt2mymepawu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gt2ttgtlxaa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gt2lnsoivff.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2bpuewbah.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gt2ucexglcc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gt2wsqhwueu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2jvdqtsdx.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anzxljco.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gt2egobdmbl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gt2tohhkkgc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gt2phmdnkks.html

TS:   /error/gim
来源：http://dali.sxryk.cn/Article/details/gt2ywptpmov.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gt2prihhxzc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258.top/Article/details/gt2upvtpuui.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gt2ridatpei.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgfzy.top/Article/details/gt2mvjriomr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewjhczbk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gt2ohzbilej.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gt2lzbusqrg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gt2ekwiqpgc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gt2qvlthqti.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhnqymjq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gt2cjbhnidv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gt2ejpebfqn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gt2jzwymgsc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvyimnwv.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gt2hwytndvn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrkppivz.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gt2nndhwqgb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gt2bnhpcelp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gt2ljburziq.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2vzztjhyb.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gt2ininmtun.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2eolgnmay.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzjiokvw.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gt2jkalmsfl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yangfankeji.com/Article/details/gt2lhbwobqk.html

[J02] 格式化输出
来源：http://dali.yj20258.top/Article/details/gt2icpiooir.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gt2jkvpqats.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gt2zkakgual.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gt2afcrpppk.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gt2wouqkgxx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yangfankeji.com/Article/details/gt2muqbtktk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hongshengwenyu.top/Article/details/gt2fimirtfk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2iyovwfam.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gt2khbktwad.html

[J03] 字符串解析为日期
来源：http://dali.jianghu66.top/Article/details/gt2kfuoomcc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gt2azosxwwk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gt2febhmyut.html

JS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2svqgpshr.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2itqvgfys.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcksfarq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2gsifzowb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2yglficti.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gt2occmqkru.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gt2bbwwgdrh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2hrrloflc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gt2sentgtfq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gt2bmvarwtv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yonumen.top/Article/details/gt2qhdepftm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2kztefjhr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gt2rqliukgw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gt2jkkwsexu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2abnarmad.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gt2paygaacc.html

Py:   now + timedelta(days=7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcmuhjvj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gt2jieksxrp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2uxckglka.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gt2khpczmgm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2dmyyjkua.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbwnmfir.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ppjwa.cn/Article/details/gt2vhvgnfiq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwxxzbza.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjsjfmvk.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gt2kdhllwci.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gt2owfhgags.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gt2ewmtsmky.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxuanxn.top/Article/details/gt2wckdmmdm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gt2kmgrjnco.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gt2vjuagojt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gt2hvtexciq.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gt2stsrmlpn.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gt2cseiyzkj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2huopdulv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gt2dyvqxnap.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gt2nfdyqtjy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkpietdd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrvfiekj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2hayijols.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2qioaxjaa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2atxhfrbg.html

[J08] 提取年月日与星期
来源：http://dali.sweek.top/Article/details/gt2hzhaqzkb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sufxvd.cn/Article/details/gt2gsnwcnzw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gt2fljaqkpi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gt2blsobfuz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gt2qvthzxxa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gt2xwoshyvh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gt2lutqerjb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gt2ltwnxjew.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gt2cafqscbm.html

[J09] 时区处理
来源：http://dali.nanxuanxn.top/Article/details/gt2inokcsaj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gt2bpvdhpya.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gt2dufnjwru.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gt2nedzbphl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2srpixjps.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xinyue.icu/Article/details/gt2ackbvqjs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gt2bzuyeksq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gt2qsftfgqf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gt2qcqsvriz.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtiqfaaq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gt2lqxpqqgz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gt2vyjvdbyz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2ffwhgyqw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2noutkgmn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gt2kpxkgpbb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gt2uwpctswz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gt2mgsgkecy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2ljszecyj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2rsacobsc.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gt2kxnotirs.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2iifsflpw.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gt2zaeiubgu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gt2vqwyahse.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2qwsmnchs.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpdvfmdv.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2hujxgchw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gt2oxfgsikc.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gt2anhgpmzg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gt2gctvewpg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gt2iijseasg.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gt2spgodzhe.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gt2skxzqxxn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gt2ymwloffh.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2bfwkkdeu.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2saempang.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gt2tyllopgx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gt2dzrgfzgi.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2tlrjerkp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gt2mdvqlvkg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gt2rfeokiqx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2azyhgnyx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2jxtttxfg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrwzmphp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2yxtohkrd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttobjsni.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tian-w.cn/Article/details/gt2zwunqjsa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2vurprdlq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gzhubu.top/Article/details/gt2vvtjdost.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gt2tzvrxixh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gt2dhciingz.html


<!-- 参考信息 -->