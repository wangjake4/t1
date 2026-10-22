代发 wailian999

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjrfwyeg.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gt2naimosju.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gt2byihnwnx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tanke756.top/Article/details/gt2hjwhivaw.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gt2hfxoldwf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gt2vphtpgpd.html

[Q68] 保存点
来源：http://dali.hywenlv.cn/Article/details/gt2ginlqeqq.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gt2olwgamkj.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhwxtizg.html

[Q69] 查看执行计划
来源：http://dali.fengsongda.top/Article/details/gt2dhzerfnb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gogol.net.cn/Article/details/gt2lztuurhe.html

[Q70] 更新统计信息
来源：http://dali.zdqjudy.top/Article/details/gt2ifjblfsd.html

ANALYZE TABLE users;
来源：http://dali.redwolf501.top/Article/details/gt2tvmjdfkq.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gt2pmgfdawu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gt2kluabhdi.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gt2lfeforbg.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2tobfbdyz.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gt2bueowbtp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gt2oqmbzpfs.html

[Q74] 强制使用索引
来源：http://dali.9152youxi.cn/Article/details/gt2ljxkrpwn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gt2cckhkrrl.html

[Q75] 日期格式化
来源：http://dali.yongpay.top/Article/details/gt2wabygwfy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2csdovfpv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tanke756.top/Article/details/gt2yqtenbzs.html

[Q76] 按天统计
来源：http://dali.fengsongda.top/Article/details/gt2rlfuhpik.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yueranfly.top/Article/details/gt2zngxekuc.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gt2jsrslqln.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gt2tetdwgvw.html

[Q78] 当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2alzuesws.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gt2totyjroj.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brutztze.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gt2dbndpzrz.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gt2ttaxzacb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2tlqpklhf.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fticoffo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2pnfalyhp.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gt2esownlmm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2kfohemfe.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gt2pbftdmpw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkmhejdc.html

[Q84] 去除首尾空格
来源：http://dali.yonumen.top/Article/details/gt2bxneajmn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlscoaac.html

[Q85] 数值取整
来源：http://dali.snrcjt.cn/Article/details/gt2saeqborn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhixingplan.top/Article/details/gt2tncdqqha.html

[Q86] 读取 JSON 字段
来源：http://dali.guowangkeji.top/Article/details/gt2gqtrbigx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gt2hxjpwsnc.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gt2jxyxtczm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gt2szfzbezr.html

[Q88] 行转列（条件聚合）
来源：http://dali.cashguo.top/Article/details/gt2olyztyxz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sufxvd.cn/Article/details/gt2muqvtqmp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2kuqonoha.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2eucjsywa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gt2opqbqaxx.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gt2jzqlffvn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxinkj.top/Article/details/gt2wopdalnk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2tohfotka.html

R. Bash 专题
来源：http://dali.xinyue.icu/Article/details/gt2sbnrhruf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2qstkdbso.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gt2ubvogztm.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gt2upalugcg.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gt2yuqshbgu.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gt2bjidswep.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gt2qtfynoun.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gt2mfcpkaco.html

readonly PI=3.14
来源：http://dali.0kj1m.cn/Article/details/gt2vjohwskx.html

[R04] 位置参数
来源：http://dali.gogol.net.cn/Article/details/gt2bbahckfj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sysykeji.top/Article/details/gt2hiyyxexi.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gt2czspqbpq.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gt2lqrdhjon.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2nclmuetf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gt2ftbtvmbx.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gt2ejojqidt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gt2bepndwsz.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gt2yokfhkjx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2qdtnzcwl.html

[R09] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gt2ksbllurk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gt2fuiifvyo.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gt2xgmkkfap.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2mbwuinir.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gt2lknaprwp.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gt2kxlcozbd.html

start) echo "启动" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2axbsvfsz.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gt2ftxdsimd.html

*)     echo "未知命令" ;;
来源：http://dali.tianlin.xyz/Article/details/gt2qujbuehv.html

esac
来源：http://dali.tian-w.cn/Article/details/gt2nkfsooig.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gt2eprjbkzn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkkbkahw.html

[R13] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gt2qscphdqh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gt2rsuriuom.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gt2ncsixpnb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gt2uwptojlb.html

[R15] while 逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2uitadvsv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gt2fcwmonxu.html

[R16] until 等待条件
来源：http://dali.jinqigufen.top/Article/details/gt2bkxdtyac.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gt2airbhboa.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gt2razpaway.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gt2lqzzprga.html

[R18] 遍历数组
来源：http://dali.jqgfzy.top/Article/details/gt2lbmtomhh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gt2tigoxorf.html

[R19] 数组长度
来源：http://dali.yonumen.top/Article/details/gt2poywmsuk.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gt2apwlyjor.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gt2vjxkqvec.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gt2jxliyywx.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gt2yzpoobut.html

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gt2ahwhlqde.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gt2crulqhqq.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gt2bcerycqj.html

[R23] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gt2ldoybjnk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yueranfly.top/Article/details/gt2tolkkctk.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gt2obeddgcs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gt2eisrmzic.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gt2guguscsd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2usevrmrg.html

[R26] 命令替换
来源：http://dali.yj202588.top/Article/details/gt2owmgsdjm.html

now=$(date +%F); echo "$now"
来源：http://dali.yj202588.top/Article/details/gt2lrfxakhs.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gt2xpigxmbw.html

echo $((1 + 2 * 3))
来源：http://dali.chenlongwang.top/Article/details/gt2qbzcdwpb.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gt2ihzeqbyr.html

echo "scale=2; 10/3" | bc
来源：http://dali.snrcjt.cn/Article/details/gt2yqbpwcdu.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gt2hasragai.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gt2dparymex.html

[R30] 函数返回状态码
来源：http://dali.jianghu66.top/Article/details/gt2czylhwsf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gt2krftaskx.html

[R31] 局部变量
来源：http://dali.guowangkeji.top/Article/details/gt2ternvsik.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gt2pzcenhiz.html

[R32] 参数个数校验
来源：http://dali.gogol.net.cn/Article/details/gt2legdpzcy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gt2rzmolknc.html

[R33] 捕获错误并提示行号
来源：http://dali.sysykeji.top/Article/details/gt2iwejpedu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gt2ewpobffl.html

[R34] 退出时清理
来源：http://dali.yuanzhike.top/Article/details/gt2zwnlucjp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gt2hjusgnei.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gt2puhyzwal.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chvwesec.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xeifvsel.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhixingplan.top/Article/details/gt2snxanxxl.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gt2cbwsujdo.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gt2ivocxbnu.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gt2qrrvocwk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cashguo.top/Article/details/gt2dowuknqo.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gt2bjfeneum.html

cmd > out.log 2>&1
来源：http://dali.guannengcc.top/Article/details/gt2ijbcpebe.html

[R40] 追加写日志
来源：http://dali.zdqjudy.top/Article/details/gt2zearmkzo.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gt2gzgzyjpa.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gt2wdowixti.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2vtzkyzao.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gt2fbttgdwq.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gt2ydtcfvlv.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gt2awcrpdbf.html

find . -name "*.log" -type f
来源：http://dali.smart0.xyz/Article/details/gt2ztblgioh.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gt2fwxceswd.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gt2jxuyrezm.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gt2wsxwmohe.html

find . -name "*.tmp" -delete
来源：http://dali.sweek.top/Article/details/gt2snvrsdor.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gt2gaougjpv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hfpthk.cn/Article/details/gt2yldaigfi.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gt2rurczlgd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2kwqgrnzw.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gt2abkpfwyk.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2sqvtewbf.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gt2acacopbq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rvhyvrbl.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gt2ieelotuj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2jxoizdms.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gt2oduknfhv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gt2yyarxydr.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gt2whivrcsf.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2cdbhjihz.html

[R53] 查看文件头与实时尾
来源：http://dali.shangyingyoupin.top/Article/details/gt2llaimrzz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gt2bcutjcnn.html

[R54] 比较两个文件
来源：http://dali.hammf.cn/Article/details/gt2apegwiob.html

diff a.txt b.txt
来源：http://dali.mhx1999.top/Article/details/gt2gukhafxw.html

[R55] 压缩与解压
来源：http://dali.wangshuangyany.cn/Article/details/gt2paucpewc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gt2rrkqepsc.html

[R56] 远程拷贝
来源：http://dali.kuanghao11.cn/Article/details/gt2ekuousdo.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gt2qrxidahp.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gt2yypgjive.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gt2foovdrne.html

[R58] 下载文件
来源：http://dali.ybcxt.top/Article/details/gt2fdnvixrm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zznicaxd.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gt2aidtuiqx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gt2gkvnnapn.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gt2jwkspcjl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gt2clezyiad.html

[R61] 磁盘占用
来源：http://dali.jqgufenzy.top/Article/details/gt2zeknmpst.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gt2tsrpogda.html

[R62] 找最占空间的文件
来源：http://dali.cucudq.cn/Article/details/gt2suamospd.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gt2tgedfvhy.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gt2jrfnlrxa.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gt2ryhkbirs.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mblsoyxx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gt2ikwnwixq.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gt2liqryzgg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gt2xwahowvf.html

[R66] 定时任务
来源：http://dali.c1oappe.top/Article/details/gt2qmavppzg.html

crontab -e;  crontab -l
来源：http://dali.zhengqikj.top/Article/details/gt2xocgtevd.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gt2kidbhqzh.html

openssl rand -hex 16
来源：http://dali.jinghuilouyu.cn/Article/details/gt2juujgccl.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqfwhfpj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gt2hkovtctb.html

[R69] 生成随机密码
来源：http://dali.yj20258.top/Article/details/gt2vpmpgxsk.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gt2shrfushr.html

[R70] 时间戳与互转
来源：http://dali.sxryk.cn/Article/details/gt2kinlogkm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnpamux.html

[R71] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2evsmpyzy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cqqwz.cn/Article/details/gt2qubevcoq.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gt2tsdjrsmg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gt2omrmtbzq.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gt2qybpzrxi.html

split -l 1000 big.log part_
来源：http://dali.cdnleiting.top/Article/details/gt2kuyikcmm.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gt2mkomtefb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2vovxvrbb.html

[R75] 导出环境变量
来源：http://dali.andypj.xyz/Article/details/gt2sqtplavm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gt2clkwrjgd.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gt2mfuhvsug.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gt2jocudghf.html

[R77] 读取用户输入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acalhypm.html

read -rp "请输入: " ans
来源：http://dali.tianlin.xyz/Article/details/gt2stmprtrf.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvjadxke.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gt2ihjgnicr.html

[R79] 解析命令行选项
来源：http://dali.hammf.cn/Article/details/gt2uhxtkzny.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gt2hsjuykcn.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gt2shjudeii.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gt2pfxaepbk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2zmignoyp.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gt2kqxmmwjo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2bgnxhfgu.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2mpgvlscp.html

#include <stdio.h>
来源：http://dali.zdqjudy.top/Article/details/gt2pbbziwga.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gt2sskyudmg.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2inylmguq.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gt2bwzugfyq.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gt2pmoneuwb.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gt2tkquiehs.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gt2kyhdmwxg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yueranfly.top/Article/details/gt2dtpfbzak.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gt2hqccscnz.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gt2ddavwzmm.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gt2csrwiwzw.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjriuztx.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gt2qgtohzdr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gt2rnqzwhsn.html

[S08] C：动态内存分配与释放
来源：http://dali.gogol.net.cn/Article/details/gt2xgbvvkdj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gt2livnzsnh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gt2aijpdcxk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gt2tegntfzh.html

[S10] C：指针与解引用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kyfaqzzd.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gt2tffiobqo.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gt2xifciclr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bijanvzg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hammf.cn/Article/details/gt2mmhdkscg.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gt2cboonomk.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gt2jcrwaazd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jcmwfuen.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijezmmzj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gt2zmrrarfk.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gt2nbntmoet.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gt2srbikkks.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gt2ubksmyyc.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gt2tfuqgkjz.html

[S16] C：位操作置位
来源：http://dali.shzxlz.cn/Article/details/gt2aycmzbmj.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gt2vzavoibq.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2lzjglesu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gt2ccuflrvc.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2fakjktzo.html

int main(int argc, char **argv)
来源：http://dali.fengsongda.top/Article/details/gt2ktrxyooe.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gt2zpkufwoh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2ugkglbru.html

[S20] C：二分查找
来源：http://dali.pycfn.com/Article/details/gt2zavtpoqg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gt2bhdshfvf.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gt2cmjuzydv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.bjfxy.top/Article/details/gt2jeczpeep.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gt2xtmdegnk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gt2ixxwyohk.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gt2dclgnfzu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gt2zzskczge.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gt2briyivjm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ppjwa.cn/Article/details/gt2mmemsdxr.html

[S25] C：内存拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ncympsjo.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gt2kcliqggz.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqsszokp.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gt2ojwnirai.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gt2ybcorvvz.html

const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gt2dandionl.html

[S28] C：静态变量
来源：http://dali.hysaishi.cn/Article/details/gt2ugytaycy.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gt2kasijfch.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gt2fmvqrniz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gt2pxrccyxx.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gt2whdvlaow.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltlivmon.html

#define X_H
来源：http://dali.ivvv.top/Article/details/gt2kaliooyl.html

#endif
来源：http://dali.yvedp.cn/Article/details/gt2ocztgibg.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gt2oxegeqby.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gt2klfizmcf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gt2kjgkrmhw.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gt2buensdmb.html

std::string s = "hi";  s += "!";
来源：http://dali.tianlin.xyz/Article/details/gt2tmwfxzfd.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gt2oikvjfoy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfgpurse.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gt2tikpqeai.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gt2htqlvgyr.html


<!-- 参考信息 -->