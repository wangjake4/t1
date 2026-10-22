代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gtrkifuvui.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gaohongyu789.top/Article/details/gtmbifxgnh.html

[Q68] 保存点
来源：http://dali.nanxinkj.top/Article/details/gtvfufdbms.html

SAVEPOINT sp1;
来源：http://dali.tianlin.xyz/Article/details/gtbehkhyra.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gtewkgqzzm.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gtlkingarp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgfzy.top/Article/details/gtwsigzoqi.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gtxyihnlfm.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjbcyvqs.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gtifwzooai.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gtpwxqqdmn.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gtchklkzzb.html

SHOW INDEX FROM users;
来源：http://dali.ybcxt.top/Article/details/gttwgmxvro.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gtppwpylxo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnqzz.top/Article/details/gtkxwgjwtd.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gtzcrouodp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zdqjudy.top/Article/details/gtrfjeumav.html

[Q75] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtwolriiyv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtugvbhuuf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gtrawxugos.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gtxfyavgrs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ydzc1.top/Article/details/gthzvpfehf.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gtdhylvjny.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkamsfrq.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gtfohzvuho.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangdashe.top/Article/details/gtabcnsgop.html

[Q79] 字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gtrglrmqpi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cqqwz.cn/Article/details/gteqatwbwr.html

[Q80] 字符串截取
来源：http://dali.yvedp.cn/Article/details/gttwbvsvms.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gtxqzfwbpo.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtmzlpmiyj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtxgokxvyz.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gtytfldjbv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtynfkzgal.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtxitfzrll.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtokegjyxs.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gtuivellav.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtfjrualwk.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gthlbwpswi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcsbnsni.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gtwlpupqwp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj202588.top/Article/details/gtlphnjvbx.html

[Q87] JSON 字段做条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtriuhzgwe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gtsfphrxkp.html

[Q88] 行转列（条件聚合）
来源：http://dali.tian-w.cn/Article/details/gtuzywkiic.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shangyingyoupin.top/Article/details/gtbqailemt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtrtidehhn.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gtcbuyfdwu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gtccbuhmgc.html

[Q90] 生成序号列
来源：http://dali.zycfv.cn/Article/details/gtohixmvfp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sxryk.cn/Article/details/gthsujxqls.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaqirhye.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gtnsqwosvm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvkjapqav.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbjxoswj.html

#!/usr/bin/env bash
来源：http://dali.sufxvd.cn/Article/details/gtenbhxhgu.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gtrrgtimnl.html

[R02] 变量赋值与使用
来源：http://dali.aizwys.cn/Article/details/gtubbdxyvq.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtqvpcstji.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnksvqhqk.html

readonly PI=3.14
来源：http://dali.guannengcc.top/Article/details/gtgvtkgyae.html

[R04] 位置参数
来源：http://dali.yuanzhike.top/Article/details/gtvxfofwbn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtlocwgmvl.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtghgkavrz.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtywijwmcf.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtqrhsoemz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gteosdbegm.html

[R07] if 判断文件
来源：http://dali.jqgufenzy.top/Article/details/gterhbrhsv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gtxhjxyqmh.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtrxdosund.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gttoxfycjp.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtxnveomlu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtublgzkfx.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gtoyhcksdt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtnjshoqws.html

[R11] case 多分支
来源：http://dali.hnxiangtu.top/Article/details/gtdismzeix.html

case "$1" in
来源：http://dali.jinqigfzy.top/Article/details/gtquqjmcoa.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gtbwqevyar.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gtnblmxzxp.html

*)     echo "未知命令" ;;
来源：http://dali.birdmap.top/Article/details/gtilzwrcld.html

esac
来源：http://dali.hfpthk.cn/Article/details/gtiktxwxzo.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gtanvilrdt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gtgxjnuhzv.html

[R13] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gtvzvjmjih.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtdbdwrdns.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gtadxehzee.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtuirmdzod.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtcuakoffd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtcvuwikyf.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gtobkxaisg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtkooxwhov.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gtpkewgipl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gtekioxyck.html

[R18] 遍历数组
来源：http://dali.meibo888.top/Article/details/gtmxijjkud.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gtkqqhcftj.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtycvczjoq.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclstxxrw.html

[R20] 关联数组（字典）
来源：http://dali.gaohongyu789.top/Article/details/gtvjlfablw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gtbllfglhg.html

[R21] 字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtfccrsqfh.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtljldcxwu.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwedfueu.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gtmbvlrlxf.html

[R23] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtcegsfqov.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ydzc1.top/Article/details/gtphosxalg.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtgjvpkqou.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gtxqnhyxyg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gtrijrytht.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hammf.cn/Article/details/gtkhlwarpf.html

[R26] 命令替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlipyjfj.html

now=$(date +%F); echo "$now"
来源：http://dali.haohaochexian.top/Article/details/gtshuehvvl.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gtmosfgsgl.html

echo $((1 + 2 * 3))
来源：http://dali.dashuyun.cn/Article/details/gtgcwgwfgl.html

[R28] 浮点运算
来源：http://dali.zhixingplan.top/Article/details/gtjmyybjzi.html

echo "scale=2; 10/3" | bc
来源：http://dali.cheryme.top/Article/details/gtrawxkdow.html

[R29] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtiyqjqppr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.haohaochexian.top/Article/details/gtbidhnlnx.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gtocdkhsqd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gtkunxzluc.html

[R31] 局部变量
来源：http://dali.316326.xyz/Article/details/gtzeizrygq.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigufen.top/Article/details/gtbwrmqfka.html

[R32] 参数个数校验
来源：http://dali.jyoumei.cn/Article/details/gtxjufeifn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtkmupebil.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gtofiegwzl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gtzrslptyk.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtgijmpvrj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtpyffkmnx.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gtsxvevrmi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.vqdsnc.cn/Article/details/gtbqqzliew.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gtvcnacpuu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtagmfvmng.html

[R37] 把输出赋给变量
来源：http://dali.c1oappe.top/Article/details/gtpkgtljqr.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapyfalzz.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gtksozbwze.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gaohongyu789.top/Article/details/gtzxdnssic.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gtjtzfewri.html

cmd > out.log 2>&1
来源：http://dali.c1oappe.top/Article/details/gtdfxkrvza.html

[R40] 追加写日志
来源：http://dali.meibo888.top/Article/details/gtwdsqzvre.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gtoboeqndo.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gtlnedxfld.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtyoedzmtv.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gtfoufeoho.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gtznnpmnni.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gtharrktae.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gtgabktdoy.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gtmwciykks.html

find . -mtime -7 -type f
来源：http://dali.zhixingplan.top/Article/details/gtohvofrkn.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gtbyoutupx.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gtlyadmmry.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gtbxxlkaam.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gthcgkketo.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gtwksmrtys.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ybcxt.top/Article/details/gtcuzvgyiz.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gtulrxhire.html

awk '{print $1, $3}' a.txt
来源：http://dali.xylfe.cn/Article/details/gtldlgapxv.html

[R49] awk 带条件
来源：http://dali.ehwqpu.com/Article/details/gtmaiazxwr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cdnleiting.top/Article/details/gtwiemsxee.html

[R50] awk 求和
来源：http://dali.aizwys.cn/Article/details/gttxyibltm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtkpxjhxmw.html

[R51] 排序去重取前几
来源：http://dali.havefunace.top/Article/details/gtfjlbixzx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gteupmfqbz.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gtkovzihob.html

wc -l a.txt
来源：http://dali.kuanghao11.cn/Article/details/gttkixncgq.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gtvfcwttns.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gtgsqtsjdj.html

[R54] 比较两个文件
来源：http://dali.shzxlz.cn/Article/details/gteykruyzh.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gtpwddknil.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gtwyrecebx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gtlwouupjj.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtqzuqduvj.html

scp file user@host:/path/
来源：http://dali.yangfankeji.com/Article/details/gtkpnbxnmm.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gtlksbefpd.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gtgrpsexyf.html

[R58] 下载文件
来源：http://dali.yuanzhike.top/Article/details/gteperuwhb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenzaomai.com/Article/details/gtlijiumvc.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtzigvgpzj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gtghafvndt.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtsgscrnhz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gtuakvdyir.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gtkwigydrh.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gtxbzocgqf.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gtacfhtjzw.html

du -ah . | sort -rh | head -10
来源：http://dali.pengpengdd.cyou/Article/details/gtnfpiwtlo.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtucxvmvmh.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gtvznmmerr.html

[R64] 结束进程
来源：http://dali.vqdsnc.cn/Article/details/gtfxygisud.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gtnpiecjht.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gtwerkckll.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtbeaijwne.html

[R66] 定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gtprzicncb.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gtkvyoijti.html

[R67] 生成随机十六进制串
来源：http://dali.cdnleiting.top/Article/details/gtwvepgvxa.html

openssl rand -hex 16
来源：http://dali.shangyingyoupin.top/Article/details/gtjrlvmgxe.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gtzbfihtos.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gtufqgeurn.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gtozhbzeox.html

head -c 16 /dev/urandom | base64
来源：http://dali.snrcjt.cn/Article/details/gtwoozfnpm.html

[R70] 时间戳与互转
来源：http://dali.nanxinkj.top/Article/details/gtopoebchr.html

date +%s;  date -d @1700000000
来源：http://dali.aibaodan.cn/Article/details/gtdoaefilk.html

[R71] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkhyuasc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tanke756.top/Article/details/gtkoyggtvl.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gtmtuzbglt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtqqcfxvhc.html

[R73] 分割大日志
来源：http://dali.yuxming.cn/Article/details/gtfteyijnm.html

split -l 1000 big.log part_
来源：http://dali.vqdsnc.cn/Article/details/gtiqgmzkyj.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gtqweafncu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gtlnavfntx.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gtlxpzziiz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ybcxt.top/Article/details/gtjhhcvokk.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gtdamkagar.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gtvzgjwlun.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gtawfzqpes.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gtycsuuive.html

[R78] 交互式菜单
来源：http://dali.yueranfly.top/Article/details/gtubkjtqib.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shuidangran.top/Article/details/gtuzxnfdfv.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gtdtiantol.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gtghuwfvgp.html

[R80] 查看脚本执行耗时
来源：http://dali.cheryme.top/Article/details/gtojbevmzl.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gtktohoodw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtifdylhrp.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gtakverkuo.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtebdfcekw.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtkyitnywa.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gtxjusyvcp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hywenlv.cn/Article/details/gtppkgdosx.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtiwyvgrpu.html

int a = 10; printf("%d\n", a);
来源：http://dali.ydzc1.top/Article/details/gtxacbuaei.html

[S03] C：读入整数
来源：http://dali.birdmap.top/Article/details/gtznoxqcvu.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gtxacsyghf.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gtxstkuqim.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrqcrfab.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtubsscncy.html

strlen(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugndcsst.html

[S06] C：字符串比较
来源：http://dali.yongpay.top/Article/details/gtxqclszbs.html

strcmp(a, b) == 0
来源：http://dali.xuanzx.com/Article/details/gtomsfgjeb.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtnybsnpqo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxuanxn.top/Article/details/gtqstafhsv.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gtuqhvyvno.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtylcswwku.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gtdtisbeyg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.svipenyu.cn/Article/details/gtmybvlboy.html

[S10] C：指针与解引用
来源：http://dali.ivvv.top/Article/details/gtyafqowjz.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gtylxuglbz.html

[S11] C：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtwfhtkxit.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gtzctkautx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtpmclccst.html

fclose(f);
来源：http://dali.ivvv.top/Article/details/gtsrnssupt.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gtnbdwifec.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtatgckoug.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gtmqlhsmzj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtlaahxbgf.html

[S14] C：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtlqlloxhe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gtuhflzafw.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gtfcwpvbcm.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gthdfgmivu.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtgnhdcpvr.html

x |= (1 << 3);
来源：http://dali.yuxming.cn/Article/details/gtdmsmuzgs.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtfjjwojba.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuanzx.com/Article/details/gtmylmrdly.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gtudcwigfz.html

int main(int argc, char **argv)
来源：http://dali.yj202588.top/Article/details/gtdqjjlstk.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gtbtohgtoz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gthlmzsgwk.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gtiyrfsdpr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtqfaybmmn.html

[S21] C：字符类别判断
来源：http://dali.jianghu66.top/Article/details/gtxhajniod.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xinyue.icu/Article/details/gtzpertjat.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gtzeohyddi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpmvsxmc.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gteklxbdhi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtlwjlivlz.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpvwwkmp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gtotkeqplh.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gtixwqkdxf.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gtlqwqhnya.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gtdrtebwoi.html

memset(a, 0, sizeof a);
来源：http://dali.jqgfzy.top/Article/details/gtdoclhvoo.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gtxhlwrpbg.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtmlspywzu.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gtmdpaemfx.html

static int counter = 0;
来源：http://dali.sufxvd.cn/Article/details/gtslhkjkey.html

[S29] C：变参函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzmiqiir.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.havefunace.top/Article/details/gtzagykfhf.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gtpohwshfo.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtdvrvdmit.html

#define X_H
来源：http://dali.sweek.top/Article/details/gtpdjujhot.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gtkbcrsfij.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtzpwpjfkc.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gtsmyrzizt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gtelbejocw.html

[S32] C++：字符串
来源：http://dali.yangfankeji.com/Article/details/gtsarjhvzg.html

std::string s = "hi";  s += "!";
来源：http://dali.yuxming.cn/Article/details/gtjvrfyygm.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gtroeomduo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sxryk.cn/Article/details/gtlxqpzfyi.html

[S34] C++：遍历 vector
来源：http://dali.yangfankeji.com/Article/details/gtyyzpdrkv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gtaefgurhi.html

[S35] C++：map
来源：http://dali.gogol.net.cn/Article/details/gtetxkxuza.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtltylztra.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtkwvkdojk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmnzgrbk.html


<!-- 参考信息 -->