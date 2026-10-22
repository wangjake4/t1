代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gt2mxfwtpfa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenzaomai.com/Article/details/gt2jxmqyjaj.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gt2lhhxlrxg.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srpjamoe.html

ROLLBACK TO sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bndiihso.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gt2szfkiutm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gt2pxezvdff.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gt2lruzzswr.html

ANALYZE TABLE users;
来源：http://dali.nanxuanxn.top/Article/details/gt2ntchxrzj.html

[Q71] 查看建表语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2agacwyzz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sweek.top/Article/details/gt2wcculejh.html

[Q72] 查看索引
来源：http://dali.dashuyun.cn/Article/details/gt2emvwzmpc.html

SHOW INDEX FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2jfalmuln.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gt2mmbuwtsc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gt2khojoced.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gt2dcwbzszl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zoemwbhx.html

[Q75] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gt2nbosyits.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghmqgdep.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aizwys.cn/Article/details/gt2ticphpis.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gt2bysbkxon.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gt2jzbijcoc.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gt2pyzhmtxe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aizwys.cn/Article/details/gt2gwkrhtnq.html

[Q78] 当前时间
来源：http://dali.guowangkeji.top/Article/details/gt2eaffwzra.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.316326.xyz/Article/details/gt2ixpovfxj.html

[Q79] 字符串拼接
来源：http://dali.yongpay.top/Article/details/gt2ldgfksrw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gt2myyvifaf.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gt2jessxeeb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2dpejuovd.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gt2weprvzyn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2qnxfigbr.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gt2ibpgcvfa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2mvayrhdf.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2xfcwvzpb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2dhesspxf.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gt2lqqasqic.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2mbqhfmqf.html

[Q85] 数值取整
来源：http://dali.cdnleiting.top/Article/details/gt2kthsrgzz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wejfxhxh.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gt2bzrglhjs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gogol.net.cn/Article/details/gt2umnbtvij.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2sipizmyd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guannengcc.top/Article/details/gt2tgkesuyq.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258.top/Article/details/gt2hslwkckc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ivvv.top/Article/details/gt2wjvsqgrh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2lxieuguo.html

[Q89] 判断表是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbpqunms.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gt2esjfimgj.html

[Q90] 生成序号列
来源：http://dali.smart0.xyz/Article/details/gt2gfxyvehu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gt2jacnkrwi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2fddqmcen.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gt2yuocjrbo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2zezpzmdx.html

[R01] shebang 与严格模式
来源：http://dali.ehwqpu.com/Article/details/gt2uojkuvbb.html

#!/usr/bin/env bash
来源：http://dali.316326.xyz/Article/details/gt2vlqtjdfl.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gt2ufcatdvr.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gt2orlsrxsu.html

name="Tom"; echo "$name"
来源：http://dali.sysykeji.top/Article/details/gt2oajbuawx.html

[R03] 只读变量
来源：http://dali.gzhubu.top/Article/details/gt2pcgopwxs.html

readonly PI=3.14
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nywvurno.html

[R04] 位置参数
来源：http://dali.jqgufenzy.top/Article/details/gt2omubvnic.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gt2nheefziw.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gt2draywvbn.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gt2ttiodtkt.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2krwlyigi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2gdpfelkr.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gt2chzgxdrt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gt2mlpqqzmj.html

[R08] 数值比较
来源：http://dali.shzxlz.cn/Article/details/gt2ghxdtmst.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2bxvandrx.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2nkrxugqc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gt2zjutgbid.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gt2bfomvvab.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ehwqpu.com/Article/details/gt2srgdzinn.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gt2igelupvu.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gt2igcswhhs.html

start) echo "启动" ;;
来源：http://dali.hfpthk.cn/Article/details/gt2vfgopgvc.html

stop)  echo "停止" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2ipulivtv.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gt2qnklhfxs.html

esac
来源：http://dali.dashuyun.cn/Article/details/gt2ldwzylzy.html

[R12] for 遍历文件
来源：http://dali.tianlin.xyz/Article/details/gt2rcytsfri.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gt2pimcigus.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gt2xyerfaar.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxzvrjut.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gt2suiaesst.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gt2jalelqlm.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2eeogxpdm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gt2bcadmsnw.html

[R16] until 等待条件
来源：http://dali.yangfankeji.com/Article/details/gt2aqmyddzl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gt2fneocqff.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gt2zpokawdc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ctyfxulw.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gt2zsgoivwb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenlongwang.top/Article/details/gt2mmkjkcug.html

[R19] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gt2hwhgnawr.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2croayfmq.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gt2ztoadeew.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gzhubu.top/Article/details/gt2kfkdhenc.html

[R21] 字符串长度
来源：http://dali.zdqjudy.top/Article/details/gt2fdsajuyq.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gt2spmbbgig.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gt2ronccdbs.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gt2zxqvddye.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gt2ndrpjrgz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.andypj.xyz/Article/details/gt2bwhnvjqo.html

[R24] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obdnyrzn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gt2layoegem.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangshuangyany.cn/Article/details/gt2inankuur.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gt2hnkogqzc.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2semetcgv.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gt2yizkkqch.html

[R27] 算术展开
来源：http://dali.wangdashe.top/Article/details/gt2yzpoeokq.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gt2pegxjawo.html

[R28] 浮点运算
来源：http://dali.sxryk.cn/Article/details/gt2ogvkzytr.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gt2zvomrpwc.html

[R29] 定义函数
来源：http://dali.xziqi.cn/Article/details/gt2ilibuzmz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gt2cbhshglp.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gt2vwldppou.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gt2rfsxbvnz.html

[R31] 局部变量
来源：http://dali.snrcjt.cn/Article/details/gt2azeprxhb.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2imgvareu.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftxmjepl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gt2zxxpkpmg.html

[R33] 捕获错误并提示行号
来源：http://dali.pengpengdd.cyou/Article/details/gt2fpavkilz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.316326.xyz/Article/details/gt2wmodyahk.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gt2txeilzbe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gt2gkufnbtq.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2txccjhub.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cheryme.top/Article/details/gt2ijqfgwwq.html

[R36] 并发执行多个任务
来源：http://dali.dianchejie.cn/Article/details/gt2ueltkibx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gt2gvyzynbl.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gt2vngpfcrp.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gt2gbsrjdpa.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gt2viofwqww.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gt2ocunykwk.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gt2dwnhkwod.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gt2atsbiatt.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gt2ohmzyysy.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gt2jchtuold.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gt2xhwfyfso.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2mfcgpaqz.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gt2gldiisvk.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2wgzwhfrg.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gt2zhhqolbl.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovqbvplg.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gt2jhtjbnyc.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gt2wgqbmgpt.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gt2ckzaywhm.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gt2oqlwortz.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gt2utcpwhho.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gt2kvjbqopc.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gt2kakawlgh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2iuiiasim.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qorddpxi.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2dxangrcd.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gt2axgkrkef.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.9152youxi.cn/Article/details/gt2egibhocf.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gt2alrjgvnx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2shklomms.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gt2rrxtbblh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gt2faunoggd.html

[R52] 统计行数
来源：http://dali.zycfv.cn/Article/details/gt2gzwfhbdj.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gt2ckuggszy.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gt2szaoqtdl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gt2ltmezynx.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gt2dvpongji.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gt2uumfzgfj.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gt2dbqkibml.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.andypj.xyz/Article/details/gt2uliijyhp.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gt2vyfqaohx.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gt2prdjudib.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gt2inrramis.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gt2nbrjlgxx.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gt2edxylpkm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangdashe.top/Article/details/gt2utcikrar.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gt2xevridvq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gt2njcoymiw.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gt2pxncpyqd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gt2cfoskejw.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gt2ocbhdhea.html

df -h;  du -sh *
来源：http://dali.cashguo.top/Article/details/gt2rgouxbbn.html

[R62] 找最占空间的文件
来源：http://dali.jqgfzy.top/Article/details/gt2yfmjrkvm.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gt2bscnnctz.html

[R63] 内存与进程
来源：http://dali.yueranfly.top/Article/details/gt2mmzxhjap.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gt2vaigqorf.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gt2otpjgyan.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gt2wlndusxd.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdqaebyt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gt2enqhwuui.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gt2ftduwsyi.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gt2rbpwxidj.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gt2qpbcpdak.html

openssl rand -hex 16
来源：http://dali.yonumen.top/Article/details/gt2kxljjjlq.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gt2exyymjyn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2mkonryei.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gt2kjxeqrcw.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gt2ilqncwwc.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gt2mfrlelnq.html

date +%s;  date -d @1700000000
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydjtrzwr.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2rmjsfqxv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guowangkeji.top/Article/details/gt2jlsffdty.html

[R72] 等待端口就绪
来源：http://dali.svipenyu.cn/Article/details/gt2iiwljchy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gt2bzlyacky.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gt2ldbfaqgg.html

split -l 1000 big.log part_
来源：http://dali.yj20258.top/Article/details/gt2ahyhsryd.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gt2avuaftho.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdrocdee.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gt2uhklbvik.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxinkj.top/Article/details/gt2cxupvimj.html

[R76] 使用临时文件
来源：http://dali.aibaodan.cn/Article/details/gt2siewnbvn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gt2ahhkyort.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gt2jizxcnee.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gt2frkoqlhu.html

[R78] 交互式菜单
来源：http://dali.iojbl.cn/Article/details/gt2tmzrzkqc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thacrojo.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gt2ppbrwaqj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2aoyokkdt.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gt2awkcanmx.html

time ./run.sh
来源：http://dali.9152youxi.cn/Article/details/gt2awyqnzlj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2tgxkrrqh.html

S. C / C++ 专题
来源：http://dali.shzxlz.cn/Article/details/gt2qbupswxg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ktsxvryf.html

[S01] C：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2dodkrwyh.html

#include <stdio.h>
来源：http://dali.cdnleiting.top/Article/details/gt2cvvfzzxx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fzhhl.top/Article/details/gt2nzzxnzvf.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gt2tlzkdveu.html

int a = 10; printf("%d\n", a);
来源：http://dali.ydzc1.top/Article/details/gt2owfgtbbc.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gt2jpgnvqhh.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gt2uiqtcnsc.html

[S04] C：字符串复制
来源：http://dali.yuxming.cn/Article/details/gt2qcvywjps.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gt2sqfqeupz.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gt2smjjukbe.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gt2bshqgokt.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2dnmcvfky.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhorstqp.html

[S07] C：数组遍历求和
来源：http://dali.9152youxi.cn/Article/details/gt2dmocvmbg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gt2mmvqllti.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gt2dnvguaic.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gt2zjqyaoeq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eludcgeo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gt2jblrdbyj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhnbkbq.html

int *p = &a;  *p = 5;
来源：http://dali.cdnleiting.top/Article/details/gt2jrwojwcb.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2gebqjhpg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gt2stzlxwek.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gt2imgamqyw.html

fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gt2fudbhumr.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhghspno.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2xkcvpbir.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gt2mwyqoill.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gt2yfyprzom.html

[S14] C：枚举
来源：http://dali.xuanzx.com/Article/details/gt2ydauesmm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yongpay.top/Article/details/gt2bbxdfwip.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gt2cunfdgvg.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gt2wqadkmjo.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gt2mwaedfmc.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gt2mhnodhkp.html

[S17] C：安全拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gt2aidvgtlq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gt2dyqqxozo.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gt2prrqdobi.html

int main(int argc, char **argv)
来源：http://dali.c1oappe.top/Article/details/gt2sgyzodxd.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gt2pirkgpss.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gt2ibktmksx.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gt2fjqxiidr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlqiefdg.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygymusev.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zarcagkh.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yurpohlw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gt2zuflcyfl.html

[S23] C：随机数
来源：http://dali.daria6918.cn/Article/details/gt2rombfnnp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ybcxt.top/Article/details/gt2aptzzjsc.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gt2nirjjbvn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gt2pqafkhsj.html

[S25] C：内存拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpeczqfd.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gt2srfawvqn.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gt2jzwurflq.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gt2zpbcouej.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gt2owyxhzal.html

const double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2ywkdgoxg.html

[S28] C：静态变量
来源：http://dali.fzhhl.top/Article/details/gt2xbfuabha.html

static int counter = 0;
来源：http://dali.dianchejie.cn/Article/details/gt2bolimoen.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gt2wjwimymv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gt2oebrnbch.html

[S30] C：头文件保护
来源：http://dali.gotoacloud.top/Article/details/gt2ucztktnx.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gt2yrojqphk.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gt2xwdnwquz.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gt2qnyslrma.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2oaxjnnja.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gt2vnheteuy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gt2lwquchuo.html

[S32] C++：字符串
来源：http://dali.chenlongwang.top/Article/details/gt2amgpjvvw.html

std::string s = "hi";  s += "!";
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdgsedbk.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gt2aojbdynq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gt2wmknlyit.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gt2gmgnbiyh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgufenzy.top/Article/details/gt2kpdrigqn.html

[S35] C++：map
来源：http://dali.yj20258.top/Article/details/gt2xlkqtybh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlercjdo.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gt2epovmyvq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2vdbwsprc.html


<!-- 参考信息 -->