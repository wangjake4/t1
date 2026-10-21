代发 wailian999

[Q63] 开启事务
来源：http://dali.gogol.net.cn/Article/details/gtctcqnzho.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gtplnnxntt.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gtprxpaspg.html

COMMIT;
来源：http://dali.nwbrower.top/Article/details/gtbczpopke.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gtydckvjrd.html

ROLLBACK;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatxfzkxo.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gtmsezhmcs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gtjwspvfol.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gtpvrqzenw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gthuetgqcf.html

[Q68] 保存点
来源：http://dali.shzxlz.cn/Article/details/gtdzkobzoo.html

SAVEPOINT sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtkgwqysbt.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gtdhznrjjf.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gtfugpaxbq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cdnleiting.top/Article/details/gtjbsctigp.html

[Q70] 更新统计信息
来源：http://dali.cheryme.top/Article/details/gtnxzjlyhx.html

ANALYZE TABLE users;
来源：http://dali.hywenlv.cn/Article/details/gtylwtbupf.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gtrqrvipuw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jlsjyb.cn/Article/details/gtdfiktorc.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gtbjupsknt.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gtmynlgpod.html

[Q73] 查看表状态
来源：http://dali.chenjidiqi.icu/Article/details/gtcnrrcqcy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nwbrower.top/Article/details/gtmdqsrfol.html

[Q74] 强制使用索引
来源：http://dali.hongshengwenyu.top/Article/details/gttttrbxcv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.quarkkingdee.top/Article/details/gtyvkgnbxc.html

[Q75] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxcnpnwb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtnlhakahj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnxiangtu.top/Article/details/gtqvaadmac.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gttvgvsugt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gtlauekrns.html

[Q77] 时间加减
来源：http://dali.aibaodan.cn/Article/details/gtuvbphqnr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchnekgkq.html

[Q78] 当前时间
来源：http://dali.gzhubu.top/Article/details/gtwrxexzoo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gtsomujiyd.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gtwcmojpzh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ybcxt.top/Article/details/gtgmxucoks.html

[Q80] 字符串截取
来源：http://dali.zhiwuduotai.top/Article/details/gtyqrnrvro.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtpgyakfnn.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtuqhdlhho.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtpeobcpnr.html

[Q82] 字符长度与字节长度
来源：http://dali.bjfxy.top/Article/details/gtaidnjdxn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtudodofqv.html

[Q83] 大小写转换
来源：http://dali.birdmap.top/Article/details/gtxksjhgfe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtaxebmpsf.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gthonargpk.html

SELECT TRIM(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtgxlskevu.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gtxkoejwyi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgfzy.top/Article/details/gtmheevhbv.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gtouovvuuc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hammf.cn/Article/details/gtfvowfehg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gtvpmopeeq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gtdreboito.html

[Q88] 行转列（条件聚合）
来源：http://dali.guannengcc.top/Article/details/gtgngscsfa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangshuangyany.cn/Article/details/gttqqizswc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj202588.top/Article/details/gtsmtmqgzd.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtdmflvpdo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hfpthk.cn/Article/details/gtmaotplhf.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gtvrhrbiov.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gtrulpnoox.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtyzqjtnpz.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gtrcpfpckr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqojjmnkl.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtbsijiriw.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndotebrn.html

set -euo pipefail
来源：http://dali.jqgfzy.top/Article/details/gtophznjjv.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtcmseraju.html

name="Tom"; echo "$name"
来源：http://dali.jyoumei.cn/Article/details/gtpuafobge.html

[R03] 只读变量
来源：http://dali.yj20258888.top/Article/details/gtsjlczcti.html

readonly PI=3.14
来源：http://dali.yonumen.top/Article/details/gtjvxrswzm.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gtrywxdfvb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gtuhteylkd.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gtojnlovuk.html

name="${1:-default}"
来源：http://dali.tanke756.top/Article/details/gtptrfabch.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gthryqidxc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gthnmnvetu.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gtpcbnvrdr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gthuirvijx.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gtphnikxio.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gtrnazhpfn.html

[R09] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gtxolntbzx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtvxgjabxt.html

[R10] 正则匹配
来源：http://dali.quarkkingdee.top/Article/details/gtxmysnnqa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gtbslevswe.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gtypfptmnd.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtcjnepoto.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gtcvndkzkm.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gtoekjncsr.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtzzkjjkxw.html

esac
来源：http://dali.jyoumei.cn/Article/details/gtjstdqiws.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gtkbrlhbhs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gtrlcuegpv.html

[R13] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gtzlbumzix.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmaembzb.html

[R14] C 风格 for
来源：http://dali.jyoumei.cn/Article/details/gtuumlgymw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtglixaxmv.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtwiynnpjo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmawktoj.html

[R16] until 等待条件
来源：http://dali.feifeiyinyue.top/Article/details/gtekgzoxhd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtuaupcpwe.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gtuuaycmpy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtphtlrqzl.html

[R18] 遍历数组
来源：http://dali.aibaodan.cn/Article/details/gttrzxhstq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.bjfxy.top/Article/details/gtmfhxplxm.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gtptuykwdy.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gthkmmbwcr.html

[R20] 关联数组（字典）
来源：http://dali.xylfe.cn/Article/details/gtdoumoxjk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtkgmmoxac.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gtxlidapnz.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtcbxjbzuu.html

[R22] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtbqrchpby.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gtzjqlyfbv.html

[R23] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtvawdovqp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aibaodan.cn/Article/details/gtbrhrpjhh.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtxykxzsqo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aizwys.cn/Article/details/gtmbnnvdeg.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gtfgnefkdg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gtdqjhoceo.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gtjiequdie.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gtovxwvogb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gtfhbiktub.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gttdzanddr.html

[R28] 浮点运算
来源：http://dali.svipenyu.cn/Article/details/gtwekdntqc.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gtdkhdnsbu.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtodbmcpol.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gtanwwfdcg.html

[R30] 函数返回状态码
来源：http://dali.tianlin.xyz/Article/details/gtgutotany.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gtcueryqpr.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gtznvyefpq.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvhlspbzf.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gteawuyehz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtwncowttk.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gtwsyjvcjt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gtlkcjeyti.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gtbgypxzfx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtytsauywz.html

[R35] 后台执行并等待
来源：http://dali.shzxlz.cn/Article/details/gtcuahfvfa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhixingplan.top/Article/details/gttjywotoq.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gtrqwohmni.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sweek.top/Article/details/gtegnvgvhj.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gttuywbjlt.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gtwsqkyipa.html

[R38] 管道串联
来源：http://dali.cqqwz.cn/Article/details/gtixnhcwtl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gtruqievib.html

[R39] 重定向标准输出与错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddtdltso.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtjecxqubp.html

[R40] 追加写日志
来源：http://dali.zhengqikj.top/Article/details/gtjkbaqmwm.html

echo "log" >> out.log
来源：http://dali.sxryk.cn/Article/details/gtisemvjyv.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gtpuydslwy.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gtupeuncaa.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdgujzqp.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtgxrndfbd.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gtcgiejyvn.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gtpgrbdyec.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gtauelvlnn.html

find . -mtime -7 -type f
来源：http://dali.fzhhl.top/Article/details/gtwpsxzyhh.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gtexhmqbeh.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gtjyfhacwx.html

[R46] 递归替换文件内容
来源：http://dali.sweek.top/Article/details/gtabmolcbi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigufen.top/Article/details/gttxzoombx.html

[R47] sed 单行替换
来源：http://dali.jyoumei.cn/Article/details/gtkpwfidka.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yonumen.top/Article/details/gtknhcdclm.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gtxdlspjbk.html

awk '{print $1, $3}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtbdwinqwb.html

[R49] awk 带条件
来源：http://dali.xylfe.cn/Article/details/gttlzhgeho.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gtjqoajbfo.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtibofckxf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xylfe.cn/Article/details/gttlwxzjzs.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gtcukzbtco.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnxiangtu.top/Article/details/gtuzulhbkg.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gtnvdymgqi.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtomnquxve.html

[R53] 查看文件头与实时尾
来源：http://dali.0kj1m.cn/Article/details/gtcxyafzfv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gtghwkgrim.html

[R54] 比较两个文件
来源：http://dali.guowangkeji.top/Article/details/gttijnfhxp.html

diff a.txt b.txt
来源：http://dali.birdmap.top/Article/details/gtfydxnnot.html

[R55] 压缩与解压
来源：http://dali.zhoulong.xyz/Article/details/gtnngedgtp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gturcydeak.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gtrthbmcpi.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gtrjqvxwbv.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxhocyok.html

ssh user@host 'uptime'
来源：http://dali.meibo888.top/Article/details/gtwegnqekk.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlxzpfoc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenlongwang.top/Article/details/gtwcyucbzh.html

[R59] 发 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtevchgglz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtablbfahz.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtccmrnmlk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdpkukge.html

[R61] 磁盘占用
来源：http://dali.dianchejie.cn/Article/details/gtmjwodalz.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gtvatdvzcx.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gtbglceijp.html

du -ah . | sort -rh | head -10
来源：http://dali.havefunace.top/Article/details/gtfexvnays.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gtvdwicqwa.html

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gtegefrfwj.html

[R64] 结束进程
来源：http://dali.jiagoushi.top/Article/details/gtmoafldvp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gtelesdxsh.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gtgvtzvvms.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.c1oappe.top/Article/details/gthbdxkory.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gtrlybjprf.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gtnruwhcrm.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtjbtrkqod.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gtsmbjiswb.html

[R68] 计算文件校验值
来源：http://dali.gogol.net.cn/Article/details/gthqowlwla.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gttcajvapn.html

[R69] 生成随机密码
来源：http://dali.gaohongyu789.top/Article/details/gtshypswbb.html

head -c 16 /dev/urandom | base64
来源：http://dali.yvedp.cn/Article/details/gtqqwvldne.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gtlkfbcnxu.html

date +%s;  date -d @1700000000
来源：http://dali.hongshengwenyu.top/Article/details/gtmzcqzfij.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtnctsvzak.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sysykeji.top/Article/details/gtuhgcvuei.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtwcpdpgwa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtqcexktuw.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gtwbdarcrz.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gtenewmtqt.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gtvkdxmhaz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocztyzgq.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gtghueqqcd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dashuyun.cn/Article/details/gthosdslko.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gtmzlbmisq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtasmlxkgo.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtwdqfanmt.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gtjpludrqc.html

[R78] 交互式菜单
来源：http://dali.havefunace.top/Article/details/gtpwekhius.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gtsfgpbcqf.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gtmushikhs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gtfqcetfld.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtsunkqcbd.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gtsvbathby.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtcpvekdft.html

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gtnrfqkjql.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqrqhpbsi.html

[S01] C：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtgpoaxqdb.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtpkepjmdv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gtwbyddvvv.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtivxeloyd.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gtwhcfztbb.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gtbipmdmlq.html

int x; scanf("%d", &x);
来源：http://dali.jianghu66.top/Article/details/gtwmvjunck.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtbmwulhhe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gtrmvngfdg.html

[S05] C：字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtypeiewpi.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gthvitqfse.html

[S06] C：字符串比较
来源：http://dali.gzhubu.top/Article/details/gtbtkpnimf.html

strcmp(a, b) == 0
来源：http://dali.cqqwz.cn/Article/details/gtvmaewwkz.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gtbdesepwo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.9152youxi.cn/Article/details/gttxnfgubp.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtripfhbtr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtwktrrhoa.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gthethqyro.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gtgobdlkhr.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gtbjgdwajg.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gthmvecflf.html

[S11] C：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtyjojmeyr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gtavarkwvx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtfocpbnrc.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtbgasijor.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtzokobwkg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtcckrwhxa.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gtpssespma.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gteoinwenh.html

[S14] C：枚举
来源：http://dali.cqqwz.cn/Article/details/gtosdgvggz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gtbkugkvmh.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtputxujtm.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gtpyjkrobh.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctqkwkya.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtibjeuwxn.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtajrfcoco.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gtezwgvpaz.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtdhukrdgw.html

int main(int argc, char **argv)
来源：http://dali.birdmap.top/Article/details/gtnmnwfozd.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gtntasmkvb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gthbhyzpex.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gtepvudife.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtuuxcvivh.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtjfjyzwuu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yangfankeji.com/Article/details/gtsiwygmxt.html

[S22] C：字符串转数字
来源：http://dali.sweek.top/Article/details/gtfciwttwv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gtdbybyfej.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gtdriooroc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gtvzrlpyxv.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gtvzxpcehm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtnlswvwgc.html

[S25] C：内存拷贝
来源：http://dali.c1oappe.top/Article/details/gtjxhawaak.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gtpzhjjcka.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gtbgjulfpj.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gtrbcnvigq.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gtnhxdvsxn.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gthobnwema.html

[S28] C：静态变量
来源：http://dali.yj20258.top/Article/details/gtukmxsdbh.html

static int counter = 0;
来源：http://dali.ybcxt.top/Article/details/gtsracrkmz.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gtfwcyqowl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gtcozgapvm.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gtjvgfxvgj.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gtlplsrdvz.html

#define X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiihztck.html

#endif
来源：http://dali.ivvv.top/Article/details/gtuxxihmtd.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gtizfzaepp.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtaocltotr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtorshvwgo.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtfsmttacn.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gtitoexmmn.html


<!-- 参考信息 -->