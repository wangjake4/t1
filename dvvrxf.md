代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtbocunkkg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gtzninwnho.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gtroqtpymq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtegoowwqy.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gtjmgxwara.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gtjwmptjbk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtektznelh.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtgahrwnst.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtuhzidfde.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtneenlumc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gtswgtzezn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gtoqvssnlj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtbtmsmmyw.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtvzfkkbhi.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gtnzviqano.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtpdofrzmp.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtiatofvhv.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtlvntnjip.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtglqlygex.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cucudq.cn/Article/details/gtcjqpyiwi.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gtgybkusbw.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gtgtwqyluo.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gtnkjtbiog.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gtznkbxvyz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtkjlmzwws.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtufxmvgle.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtjclwtfta.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258888.top/Article/details/gtvqsbysyj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gtacmytjzn.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gtpmbmldub.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gthnumgqsk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsggkkpfz.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gtqctxdkik.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gtklqwugxd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtrcbgvyia.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtdkcgndet.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gtabsrddao.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gtorqstyof.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gthlqzjmch.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtotoodoek.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gtyflgeayg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gtvcvmeglm.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gtjpbwqvok.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtddqwisqc.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtsmukmwjx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gtlzvcnpay.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gtvarotext.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtnmudjigc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtswfnbeqx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gteugtsxpq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gtrhflkwia.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtdxeggrjd.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gtymwrmkvp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gtfnjqrocq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.c1oappe.top/Article/details/gtpowjhegg.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckdvrjyz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gthqhwfzxe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gttecpyphg.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gttloukics.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gtfafwegfz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfuzzcqh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gtltnxtsis.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gtfmsmrxfc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gtmexdmbxq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gtbqyrmged.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gtyeebqfbh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gtkfkmfqfu.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtghepcdqb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gtjjywcmma.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gtdjujvepy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtbsgjejju.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gtepbkydxx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gtaxyqxqzh.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlxzzjqg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gteaigkkbf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gttwfwvhud.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtazcsvopk.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gtkkswdfwj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtpnpxrapv.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtfgjwnwls.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtxzagwmwc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtswcmixeo.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gturdgubhu.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtfaolmsfq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gtybabdixt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gtyifmngbf.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtamrprbth.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.snrcjt.cn/Article/details/gtuytbvmhl.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gtadydjada.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtyitsbanz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gthpguhctr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.feifeiyinyue.top/Article/details/gtbacjpxmj.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gtjwqbirhy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gtfcmupogk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtockepqwk.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtcskcjyke.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtkrbvarff.html

[I03] 提取捕获分组
来源：http://dali.ivvv.top/Article/details/gtxbiqpawz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gtjrcpguno.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gtravmgodg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cashguo.top/Article/details/gtocfelllv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gthtbmipqp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtqkkzrsif.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gthxfqmsok.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtvlfcbhce.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gthijawcli.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gtpstwubbw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gtssxeuxzm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtwcnzmzwh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavaokokn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtqkynowjq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtwrooffck.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilaehrdn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gtejknpwlz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtznpfreou.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gtwvoofhbk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gtxhhyhflq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gtciegmvpf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtnplybdli.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtcwvnodki.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtrsvrosjc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gteldnzgjf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtfedzdasd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gtymahzyeo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gtvtxowvsc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtdovjqkvs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gtbeskpvub.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtsuiispyr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gttqhnbxkc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtgzqdumna.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gtzpxvdetb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gttedoenxz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gthxwczdqa.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gtlaacmeve.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zycfv.cn/Article/details/gtqoykllwl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtmjdeycbd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gtozjywdeh.html

TS:   /error/gim
来源：http://dali.wangdashe.top/Article/details/gtuowrqxuw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258.top/Article/details/gtxmsvwzoe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gtzcouqpej.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gtesmtyzdm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gtgvrfgbnm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cashguo.top/Article/details/gtqscnyihx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gtstjtxlkq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtxpfcrygt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtzgnaptky.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gtcvmyyuju.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtkrngrsxv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gtetfbitjo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gtibytqnxw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtfzikblgp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtrhnkkwri.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gtxdxmqvdi.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtylodliuq.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gtnzqzyfkb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gtbkvrpgao.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gtxiosvxqt.html

JS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtslyvgixj.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtwoyaifwy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.snrcjt.cn/Article/details/gtuqvmhkal.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gtjfxotnbl.html

Ruby: Time.now
来源：http://dali.zhixingplan.top/Article/details/gtdqojnszv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guowangkeji.top/Article/details/gttslofgsx.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtgefwpeqt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtkxkippry.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtgpsvgpnm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gtnlntlslv.html

TS:   d.toISOString()
来源：http://dali.jiagoushi.top/Article/details/gthakzvrfd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtsfqpcrgy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tian-w.cn/Article/details/gtdenkumde.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtjsfobhfd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknuhggfn.html

[J03] 字符串解析为日期
来源：http://dali.meibo888.top/Article/details/gtoieylfvb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gthmwykrlc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gtenrjnmpm.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtythtfmou.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtwssrozxc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtypmcfmgf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdupuwsp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtjfxgafov.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gtelcddqjw.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gtlsvqqpru.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtzkxrxjoh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaaazmag.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtcrleowiv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gtxcmnnxdi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gtxwmrwkvu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gtjuiloyfu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtmyxljpsx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gtlvensmcw.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gtunnrgqlz.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gtqafjrwht.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gtkqimwcam.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtxutsdgzh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtyzqxwcdd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtfvhogozo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gtwkdrxqgq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dianchejie.cn/Article/details/gtsyqnctoi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtsmnfntzv.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gtmdmssset.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gtggxlxiqa.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gtcwxnoevm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gtgygxclrk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gtomtkrrsk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gtsmiozvxy.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gtapuxqkeu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gtqharkzfn.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtvdugxpdn.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gtchqhulko.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtujsviphv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gteoroyjcc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtsmojkexn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtaudclsqt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusgcnful.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gtsugitubu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtqgnmkvdr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtjhmxjfhj.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gtoxkodrua.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gtdawbpwwc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtakxkecrm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gtpyunhnou.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuanzhike.top/Article/details/gtxocjbwsf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gtnlqitmep.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gtrczntdkm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gtbaprhjqe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gtrrmqaxky.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gtnbpvrcmm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtxajhonqv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gthmehclca.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtjglgdwin.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtzlinwvzu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gtavqcmvod.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gtdnsidmgi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gtyyfflubl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gtqukemxsi.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gtyxnlyfts.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gtdwxcnlto.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gtwjyjdcza.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gtkfqapvnk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gtzsmrxfdi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtosaeyyeh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gtpbdxwvas.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhaomingkeji.xyz/Article/details/gticrffisy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtyvcxkgoh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcftactbk.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtmhwfhylr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtncwqjbsx.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gtvqlxqshn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtilazuclz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtcxmaslig.html

JS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtchqdhcob.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtczpdnaah.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gtixbfyqqr.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gtfeuvhqsr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.316326.xyz/Article/details/gttpeifiji.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.svipenyu.cn/Article/details/gthxwzzrql.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gtfszbsxly.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gtbkgpyrsw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gteicjiyar.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtvullfgst.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtdrgrsuvh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtmvcvqdoq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtomsprzkx.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtbuzwmvem.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswcvhyll.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gtgvjyrpgv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtsmhcnzdo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gtxqhbqjpk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhtapywe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtxqybfakq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gtxtythdmo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gtuhwwlmep.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gtgdtpbvos.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gtjofhjmse.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtsfubnmrc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dashuyun.cn/Article/details/gtfttqvjbq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gtbzwgdpkt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtaczpzbex.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfulopvma.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtcwatxmhr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtqsnkpzid.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtzqwhiqre.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gthttqrhml.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gtafyuties.html

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gtjrwbjrvf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sysykeji.top/Article/details/gthwbnwutv.html

JS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtgzugafbn.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtwussljqu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gtavnkdgnk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gthvawqlrv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gtuvovcevp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gtcwjcfkbh.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gtjiusimqz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj202588.top/Article/details/gtcgpajtaz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gtkhzplfzu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtdxrbduqt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtkuyufnmp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hammf.cn/Article/details/gtsutrstdq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtacvohsol.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gteykuybkg.html


<!-- 参考信息 -->