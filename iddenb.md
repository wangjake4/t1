代发 wailian999

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gt2ygtirokc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2yrphyzda.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gt2epnxsxrv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gt2upsdbasv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.snrcjt.cn/Article/details/gt2cervhbcs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2pzrijlga.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gt2wrocwinc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gt2enqbrisc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gt2qaplqszk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gt2jynsejno.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gt2nmmwqihz.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gt2vuuimynb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gt2adkuyoke.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2usoyiuwx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2flocafng.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2hmbhncfj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2trsrjzgx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsbudhm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gt2hudjobwf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2wslxwnkk.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gt2efoqhcjz.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gt2wvmqzrhe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvqdhqza.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2bbaikvbr.html

TS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2ynacjcca.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hntlqogp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gt2usetfaru.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gt2vkjttevn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2fumxrbao.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gt2nqyljqbb.html

Py:   class MyError(Exception): pass
来源：http://dali.snrcjt.cn/Article/details/gt2ruhfqofh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2ghjjajeq.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gt2ithsqscx.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yaymfbov.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2ylfddtna.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gt2terhblia.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xikbyygw.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gt2ahzwisys.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gt2pdiajqfm.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gt2lnryhawj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gt2qgvrfhiv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gt2sbxbjdpe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gt2ayumygjz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uywnwgbo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gt2zinzvkeo.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gt2pencjheb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmmgrjjv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gt2fbqaonqc.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gt2svlkdtmf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2gfqpzowi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gt2yaqyobtz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gt2gfmxlbjh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bubsmwqx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gt2soggdwgj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gt2eytxfhad.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gt2lrezrskc.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gt2iwghiqpz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gt2sgzvkgwa.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2idxfmrqy.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfpamakw.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fruarjqr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gt2nrlsgosg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.meibo888.top/Article/details/gt2ycpnvlja.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gt2yggiknae.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2heimwhdo.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gt2wofhjggp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gt2bwfnyerd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gt2ijjnuion.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gt2vruyyajf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gt2fbkqfbkc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gt2ggunlotx.html

Go:   err.Error()
来源：http://dali.tianlin.xyz/Article/details/gt2gieoamld.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgtxvxld.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gt2hpzorssh.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gt2oucffjiu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.smart0.xyz/Article/details/gt2fmuwssai.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gt2sbwacgap.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gt2upnqqhaf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gt2zcrneotf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gt2bftnjjnx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gt2xuisnzbi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gt2adkypidz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gt2gvizgiee.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gt2clpfqpdf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gt2nrqxdkqt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gt2sddspvlc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2gbjbraim.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gt2tuxekrci.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.bjfxy.top/Article/details/gt2ndczpsgs.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gt2ncnoovuq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gt2cmhngzsu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2zmvjgbbh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2xjtdocfl.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2sungskcr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2kyezfidt.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gt2oebwxfly.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvffafip.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2iunhhpsz.html

JS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gt2sgwpadwf.html

TS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gt2zdbueiap.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gt2nugkilgp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gt2txwcxsby.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2raeqexep.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gt2hdxdmckt.html

[I02] 提取所有匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2vrfjwmzn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2fjpqhdqh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gt2olaywotw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gt2asncekrs.html

TS:   s.match(/\d+/g)
来源：http://dali.jiagoushi.top/Article/details/gt2tzhszrbm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddgqcvjd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gt2kfewndmd.html

Ruby: s.scan(/\d+/)
来源：http://dali.yonumen.top/Article/details/gt2olzblslb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gt2xzlcwvkd.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gt2bwqsupor.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shuidangran.top/Article/details/gt2vrqtpokx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gt2zlwiyryf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cdnleiting.top/Article/details/gt2hhuaknnl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gt2xjszjrdy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gt2lcxavfid.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gt2pcowzfho.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gt2iaksieqx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gt2bhqcnodi.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gt2sottavfj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sxryk.cn/Article/details/gt2rgceqzvj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gt2ijmifqht.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2zsqqmagr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2srobforf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynmxacnv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2hmixaolm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gt2epafjiol.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2idurxats.html

[I05] 按正则拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2jezpuuoi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.snrcjt.cn/Article/details/gt2klfyehua.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2fophrlma.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2lkjrfrud.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2kgoenmjh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhengqikj.top/Article/details/gt2ouableuj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daxiang520.top/Article/details/gt2xuwkcasx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auqdiics.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuanzhike.top/Article/details/gt2yhmzbkhg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.havefunace.top/Article/details/gt2xlqjanuf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2xpoksovx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gt2iuqwyedj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2estjdxpz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fixepgyv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2izkiysnb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gt2ymtzqnyv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2albqvpmg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2yobvnjwu.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gt2oxjhqzdr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gt2qedgotlc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gt2uleweszv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gt2knptypfs.html

TS:   /error/gim
来源：http://dali.zhoulong.xyz/Article/details/gt2yvsgjaqm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxwtpbps.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlviybdl.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gt2kuojgicn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhixingplan.top/Article/details/gt2fwxmdhrc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ivvv.top/Article/details/gt2zqiovely.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrlkinwo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gt2jcyiouou.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gt2szvhpusg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gt2ysuqozao.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gt2jppuynjz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hyhxeufz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.0kj1m.cn/Article/details/gt2dwtgjcpq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gt2oiwdosbe.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2zqrubnoz.html

J. 日期与时间
来源：http://dali.jqgfzy.top/Article/details/gt2yspfbzim.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2auoolsby.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gt2qyzdsibe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gt2kckdpjiz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gt2kownyhaf.html

JS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbzypzut.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gt2rppzhjkg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gt2kagyoipo.html

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gt2gdlfcelr.html

Ruby: Time.now
来源：http://dali.zhengqikj.top/Article/details/gt2jdqcakyn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzfgfdcl.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gt2fkwohros.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfhapbms.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gt2gnftmkjn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gt2tedowkck.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gt2ptwukbnk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gt2jjyysrqw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gt2myxoutua.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2ktettiup.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gt2lbwgavwn.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gt2wgijmjfs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuanzhike.top/Article/details/gt2wtrwiuow.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gt2zwoellqt.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2kodafljx.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2rifsoynf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2jobodxjj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpjvegdl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2ifdsdknk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gt2ntoquidm.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gt2lejtkalc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gt2ucneepky.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gt2hxknxars.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gt2uxofktab.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gt2vcizvydj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2xyowpyno.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2cxrrskhr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gt2unrxyivt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2axixoznb.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gt2jhqngwvf.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258.top/Article/details/gt2abvppprl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gt2eblqiqje.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gt2yfljdonh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gt2mvtzdeaz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gt2haqwukro.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gt2dtgrpkjo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gt2lynjtqrd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aibaodan.cn/Article/details/gt2fputrffd.html

[J06] 计算两时间之差
来源：http://dali.xylfe.cn/Article/details/gt2nutqsalc.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2arrutymk.html

PHP:  $end->diff($start)->days;
来源：http://dali.jyoumei.cn/Article/details/gt2bcjbmsaq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.mhx1999.top/Article/details/gt2cgduomhy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gt2qkdlxzoa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gt2odnsomfw.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcmslmga.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gt2idijzazt.html

C#:   (end - start).TotalSeconds
来源：http://dali.pengpengdd.cyou/Article/details/gt2jadxcqoz.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gt2zqwitqfm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2aeblvyxz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipctrujn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gt2vyrbdmpx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2foeovuct.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dawmthma.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gt2erydhqdq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2bwfdbsff.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmdojtl.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gt2yodqiusc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gt2youckvea.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gt2nudjkoma.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gt2mrcnlrza.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gt2ysjnbawr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gt2abyxovtj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gt2ogweookl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cashguo.top/Article/details/gt2kvurenxo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gt2yqdqlfpt.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gt2gthiavuq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hfpthk.cn/Article/details/gt2eecdjcrn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gt2lhitxzcf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2dzxorbto.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gt2thnnzoih.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gt2gpotiwuq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dianchejie.cn/Article/details/gt2nomflixa.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gt2xnrbbqjz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gt2cwvdgpnf.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gt2glzfxomj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gt2xbgnajde.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2obrvrssl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gt2nbyinqho.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhwwwahx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sweek.top/Article/details/gt2wphmjcoo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gt2nzgxrgtn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gt2fomrhmvj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gt2hvuwoqcn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bcxnjagt.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gt2ngkpswvk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2sppbphql.html

[K01] 对象转 JSON 字符串
来源：http://dali.tianlin.xyz/Article/details/gt2dsqporcj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gt2bywtiemt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gt2pxkxaagy.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzsmdeqg.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gt2wofwoptc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gt2hraaqyrf.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2gojuwymw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guowangkeji.top/Article/details/gt2gxxlmybr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gt2jalayhum.html

[K02] JSON 字符串转对象
来源：http://dali.yuanzhike.top/Article/details/gt2zvrywtjy.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gt2tbpsyjcj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wburtxri.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ldgewqgv.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2wnltrmyf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwertni.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fkfbprtu.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2hxnepbcu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gt2dfbgwbbh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gt2prjnwobr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2ckzymbqq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gt2dvnlsnjv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2asorbvmx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2vwdbutor.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2roumeutc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gt2fhmidvwl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gt2kzbjntbx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gt2dnpeyftu.html

[K04] 读取 JSON 文件
来源：http://dali.daria6918.cn/Article/details/gt2gthstoha.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gt2paakgvsb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gt2mdidxtdx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2kkvmgmpo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2ksisenay.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2jfvupmyk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gt2usuaxsjr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2dobbxvav.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2uqgzyzlm.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gt2gzzotton.html


<!-- 参考信息 -->