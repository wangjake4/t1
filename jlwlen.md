代发 wailian999

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gt2fjjuivyq.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gt2tzngcsmh.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gt2gaxtsyhg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fcimbnnq.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgazuimo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcendmlv.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gt2fbhsvjto.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gt2ueaskkly.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gt2wnppzmrd.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gt2lyeftqci.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gt2rdozdtfe.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gt2sbcweuvz.html

ANALYZE TABLE users;
来源：http://dali.nwbrower.top/Article/details/gt2bgusnkbs.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gt2xjkeflbe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gt2fipusnxq.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gt2dvfrszhf.html

SHOW INDEX FROM users;
来源：http://dali.hammf.cn/Article/details/gt2pkbbwexk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hebqfeor.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.bjfxy.top/Article/details/gt2ydajobso.html

[Q74] 强制使用索引
来源：http://dali.hammf.cn/Article/details/gt2qqqxbfgv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gt2tcojxjnf.html

[Q75] 日期格式化
来源：http://dali.birdmap.top/Article/details/gt2mwzwbqwc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlucshqj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gt2ndvtgpie.html

[Q76] 按天统计
来源：http://dali.316326.xyz/Article/details/gt2djrtaaho.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ppjwa.cn/Article/details/gt2xnmvhksi.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gt2oyntzcan.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yongpay.top/Article/details/gt2yasembgk.html

[Q78] 当前时间
来源：http://dali.smart0.xyz/Article/details/gt2cxlwukmg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.mhx1999.top/Article/details/gt2dhcssaom.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gt2yjwvrxqz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gt2utnnpzgu.html

[Q80] 字符串截取
来源：http://dali.vqdsnc.cn/Article/details/gt2zrmfbofh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2sbkbtinc.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gt2abocsizf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2ypjdbtss.html

[Q82] 字符长度与字节长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2tlasftxs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2kkxnzbut.html

[Q83] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2ijcldmiz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2acgjfnyr.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gt2vtqsmjpj.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2zbhpxbgp.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdzwmbzp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhixingplan.top/Article/details/gt2fxsmbumr.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gt2shdvsizr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.316326.xyz/Article/details/gt2nkiwlufy.html

[Q87] JSON 字段做条件
来源：http://dali.0kj1m.cn/Article/details/gt2frzbqean.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gt2ffvixuvm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2qufzahsn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.haohaochexian.top/Article/details/gt2dwocguxh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2zlrvndtj.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2kdemtjri.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gt2jhjcdwpj.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gt2jbutojqr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.haohaochexian.top/Article/details/gt2hcscsbmx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2vrgdfjnv.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gt2ybrxvbwd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2emajqhqn.html

[R01] shebang 与严格模式
来源：http://dali.meibo888.top/Article/details/gt2nfhktsab.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gt2pdhqqhja.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gt2vqxgjdoh.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gt2lpzpeepb.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gt2sqrqqnig.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gt2thdiykrf.html

readonly PI=3.14
来源：http://dali.aibaodan.cn/Article/details/gt2jsxyypvr.html

[R04] 位置参数
来源：http://dali.cqqwz.cn/Article/details/gt2kmdbkvpm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gt2rrauqufj.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gt2uebwlusb.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tshtasmu.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2vgrvdiet.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gt2ujsqblmg.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gt2himfdbad.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2mzgmhstv.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gt2mfzdftdo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2mltugcwy.html

[R09] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gt2ttyjctom.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gt2gcrdnbgc.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2slkhynfo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gt2xzqyrdxm.html

[R11] case 多分支
来源：http://dali.gaohongyu789.top/Article/details/gt2vajugpmh.html

case "$1" in
来源：http://dali.ivvv.top/Article/details/gt2yemfseqg.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tumcihpo.html

stop)  echo "停止" ;;
来源：http://dali.yongpay.top/Article/details/gt2hgcqkqwd.html

*)     echo "未知命令" ;;
来源：http://dali.daria6918.cn/Article/details/gt2iiosuaih.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gt2jwcvfrrp.html

[R12] for 遍历文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2juhstoia.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gt2jjkjqipl.html

[R13] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dckofoiu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2xfpdgwcy.html

[R14] C 风格 for
来源：http://dali.fzhhl.top/Article/details/gt2etygbmtq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gt2jkejzsuf.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gt2tdhkhlgp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gt2uvbrhnaz.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oyeafymn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gt2bbckyimq.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gt2lbvewxnq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2efobfabk.html

[R18] 遍历数组
来源：http://dali.cdnleiting.top/Article/details/gt2qokmlfrc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gt2pardoucp.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gt2vhpyhtxu.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gt2bamclwas.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gt2kdvilkae.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gt2dkdavbhg.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gt2scqhfzjp.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gt2nrkttcap.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2bquadrqm.html

echo "${s:0:5}"
来源：http://dali.yuxming.cn/Article/details/gt2ucvdamdw.html

[R23] 字符串替换
来源：http://dali.sweek.top/Article/details/gt2gynrcwlg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pokyrkcr.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2uyqnphhc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gt2uhviwltl.html

[R25] 去后缀 / 去前缀
来源：http://dali.meibo888.top/Article/details/gt2qnkfwbuy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hysaishi.cn/Article/details/gt2txvxgibq.html

[R26] 命令替换
来源：http://dali.sufxvd.cn/Article/details/gt2vcovgeky.html

now=$(date +%F); echo "$now"
来源：http://dali.hfpthk.cn/Article/details/gt2goqvwmij.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gt2szkutcle.html

echo $((1 + 2 * 3))
来源：http://dali.fengsongda.top/Article/details/gt2kpcnymua.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gt2godhplfr.html

echo "scale=2; 10/3" | bc
来源：http://dali.kuanghao11.cn/Article/details/gt2pmbvinli.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gt2zhaswvkv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pycfn.com/Article/details/gt2dxsgefeb.html

[R30] 函数返回状态码
来源：http://dali.chenlongwang.top/Article/details/gt2wccugfve.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gt2vbobpxks.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gt2gvbwscsn.html

f() { local x=1; echo "$x"; }
来源：http://dali.9152youxi.cn/Article/details/gt2fdflcyrr.html

[R32] 参数个数校验
来源：http://dali.shangyingyoupin.top/Article/details/gt2cxgkcepa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mufrjfri.html

[R33] 捕获错误并提示行号
来源：http://dali.cdnleiting.top/Article/details/gt2dcecutvn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gt2rerjfcnc.html

[R34] 退出时清理
来源：http://dali.chenlongwang.top/Article/details/gt2opwfegax.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2pclzxlvr.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gt2qapvmxeg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shuidangran.top/Article/details/gt2zpozdajl.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gt2sqjmnsrg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2necxclql.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gt2roevbvhp.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2nxfclejz.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gt2szdrlfkp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pycfn.com/Article/details/gt2djgpraww.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykyzrzza.html

cmd > out.log 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfshzxal.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gt2frheylru.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gt2ddhrqtkp.html

[R41] 丢弃输出
来源：http://dali.ydzc1.top/Article/details/gt2esdsjqui.html

cmd >/dev/null 2>&1
来源：http://dali.ehwqpu.com/Article/details/gt2wkyzodtk.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gt2aplzqryq.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2qwkkcfrl.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gt2pdnbojoz.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gt2aivlkosu.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gt2zzcvdord.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gt2nwwzcshn.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gt2byyyyzkn.html

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gt2fqtbeqdy.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gt2dlizbbyg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gt2zgmfuogm.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gt2cmraarmt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2argcddti.html

[R48] awk 取指定列
来源：http://dali.aizwys.cn/Article/details/gt2onlpwmzz.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2cqnleuhe.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gt2bbsfexdh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfelxihu.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gt2cqfvpjgp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gt2wclujpgc.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gt2jkakfnnw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenjidiqi.icu/Article/details/gt2znhfhrkj.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gt2ytqzknjl.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gt2ktojsocd.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gt2pddhiqsa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yueranfly.top/Article/details/gt2jjvzqswo.html

[R54] 比较两个文件
来源：http://dali.ydzc1.top/Article/details/gt2yflgeiyg.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gt2yypfiwqk.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gt2hjauarjl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gt2pozisptf.html

[R56] 远程拷贝
来源：http://dali.havefunace.top/Article/details/gt2ztpesetv.html

scp file user@host:/path/
来源：http://dali.xuanzx.com/Article/details/gt2aaixzkmz.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gt2wgbibsgc.html

ssh user@host 'uptime'
来源：http://dali.chenzaomai.com/Article/details/gt2gpingrro.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gt2lquwmvqt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guannengcc.top/Article/details/gt2vifhepia.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gt2lwrucwew.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gt2apwyhutz.html

[R60] 只看 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gt2jxhhkenh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gt2dojrfdyn.html

[R61] 磁盘占用
来源：http://dali.hnxiangtu.top/Article/details/gt2rjuohkda.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gt2gmctpbai.html

[R62] 找最占空间的文件
来源：http://dali.redwolf501.top/Article/details/gt2ggmpfffs.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gt2ckntvwat.html

[R63] 内存与进程
来源：http://dali.ivvv.top/Article/details/gt2xoymozjz.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gt2nxrdzxsh.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gt2jvfhixkh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jyoumei.cn/Article/details/gt2qvlzdjjq.html

[R65] 查看端口占用
来源：http://dali.cheryme.top/Article/details/gt2wgzvpqte.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gt2bgmxqiyw.html

[R66] 定时任务
来源：http://dali.vqdsnc.cn/Article/details/gt2gclhgdja.html

crontab -e;  crontab -l
来源：http://dali.tanke756.top/Article/details/gt2mhxwvsuu.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gt2zqkuwqkt.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gt2wojahaia.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gt2qhwoabmn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2rnvhowyt.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gt2iyjzqkma.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gt2kygpeoqj.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gt2hfckagbd.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gt2jrexxvkh.html

[R71] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2cpvpldzh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpajhtvv.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gt2rfhvewiz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gt2hbtlcpia.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gt2xaczndbn.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gt2sbfokbup.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gt2vtwnvsxl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2sbmwbjpj.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gt2nzzbinzf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gt2jplqhiaq.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwmkaavy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gt2dkpeaaff.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qlszafio.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gt2mwqkmrsn.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gt2ndbcfztu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gt2rtlxhlwu.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gt2tnxbkylp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2numsutxx.html

[R80] 查看脚本执行耗时
来源：http://dali.guannengcc.top/Article/details/gt2aszdqyob.html

time ./run.sh
来源：http://dali.birdmap.top/Article/details/gt2hatuoxnv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2mptndpqb.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gt2pktlkyuo.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2twrlznzg.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2otrmhirt.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikyfydzo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oasvvoql.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gt2iphcwemm.html

int a = 10; printf("%d\n", a);
来源：http://dali.birdmap.top/Article/details/gt2pyttnzzi.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gt2hxpqfglg.html

int x; scanf("%d", &x);
来源：http://dali.hysaishi.cn/Article/details/gt2nybbxwwv.html

[S04] C：字符串复制
来源：http://dali.chenlongwang.top/Article/details/gt2scutbsve.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gt2nacflmwe.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gt2qotxljde.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gt2aebxylcx.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gt2cehxofox.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2xysbzttx.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gt2iuexzafm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gt2hqawinid.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gt2hvewrydy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gt2usytoskn.html

[S09] C：结构体定义与初始化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjxbdxys.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gt2xzgmpgns.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gt2mroljkjy.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gt2dsozptgb.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2wuphgjqf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gt2hxtptruh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gt2lqfivovp.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gt2cgakdcjh.html

[S12] C：写文件
来源：http://dali.fengsongda.top/Article/details/gt2pcpxdqpa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gt2aodphehm.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gt2lajgmfbi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gt2nvkilflh.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gt2chamufft.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gt2dxsexxus.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gt2ogwgsihk.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gt2nejvbfuf.html

[S16] C：位操作置位
来源：http://dali.yuxming.cn/Article/details/gt2skurchcp.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gt2pocnpqkm.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2sjmkdlwd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cedqtbva.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gt2lttbnwwb.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gt2qsfhngil.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gt2sluhsnnh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gt2njklzevk.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqqcjpwu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2ywmhptqw.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gt2tmcexhyv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj202588.top/Article/details/gt2qbwverqw.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gt2mibruzfm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkosizok.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gt2wiehqzjl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gt2ewuljkjv.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2drczcllf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gt2txusgemz.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2tesemdwo.html

memcpy(dst, src, n);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2covoetlb.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gt2jixbhzrc.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gt2jxtzrxgb.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gt2chxdspjn.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2ijhglhwe.html

[S28] C：静态变量
来源：http://dali.iojbl.cn/Article/details/gt2xhlpjxmd.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gt2hxbvwxik.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gt2nrpuoudw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gt2pwnhwcxn.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gt2ybmircmp.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gt2prulnxbl.html

#define X_H
来源：http://dali.yvedp.cn/Article/details/gt2yxawofur.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gt2zddnxyuk.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gt2moyaerve.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gt2radfgjjo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gt2wnqvlbzl.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gt2fgdabqpd.html

std::string s = "hi";  s += "!";
来源：http://dali.yongpay.top/Article/details/gt2obvoljbs.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmbgdsoa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvejforp.html

[S34] C++：遍历 vector
来源：http://dali.cqqwz.cn/Article/details/gt2ouszavyt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gt2jnlduaji.html


<!-- 参考信息 -->