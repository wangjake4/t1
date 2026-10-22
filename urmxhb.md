代发 wailian999

[Q65] 回滚事务
来源：http://dali.yongpay.top/Article/details/gt2ymidnphf.html

ROLLBACK;
来源：http://dali.nanxuanxn.top/Article/details/gt2gcgshxdb.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gt2jbnbzfzz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aibaodan.cn/Article/details/gt2boknzhzh.html

[Q67] 设置隔离级别
来源：http://dali.jyoumei.cn/Article/details/gt2lmxpjfab.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nsjpgkuj.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gt2mxwnokse.html

SAVEPOINT sp1;
来源：http://dali.yvedp.cn/Article/details/gt2icqjsaua.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gt2bmawfkfk.html

[Q69] 查看执行计划
来源：http://dali.hnxiangtu.top/Article/details/gt2ruujelwc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gt2bgafueag.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gt2gqmirees.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gt2tykxmnig.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gt2eehxeetu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuanzx.com/Article/details/gt2elmtqmwq.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2widetplh.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rdaovpcp.html

[Q73] 查看表状态
来源：http://dali.hnxiangtu.top/Article/details/gt2dkupubxr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.iojbl.cn/Article/details/gt2ldtdgztw.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gt2xsnodptp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gt2vzodwkhp.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gt2yuwxzmzw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2howadfey.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guannengcc.top/Article/details/gt2wregbktm.html

[Q76] 按天统计
来源：http://dali.svipenyu.cn/Article/details/gt2pgxlnohk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gt2gbzlqshg.html

[Q77] 时间加减
来源：http://dali.aibaodan.cn/Article/details/gt2debprdfo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrmrunqt.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gt2ttrmahvg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gt2loxhbmrg.html

[Q79] 字符串拼接
来源：http://dali.sxryk.cn/Article/details/gt2skvlladu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gt2rbaklesr.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aozkcnyj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2qcushexq.html

[Q81] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gt2ikkqdrhu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2xkxobywq.html

[Q82] 字符长度与字节长度
来源：http://dali.snrcjt.cn/Article/details/gt2jjjkeqsp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2lldbxnai.html

[Q83] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gt2dkrfabif.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxwcewlz.html

[Q84] 去除首尾空格
来源：http://dali.yonumen.top/Article/details/gt2wdzfknho.html

SELECT TRIM(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2bticunwc.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gt2vlxciveb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gt2ujifoxiu.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gt2fdbqdyii.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gt2jknfntvs.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gt2ubzjpdvx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwbewur.html

[Q88] 行转列（条件聚合）
来源：http://dali.cheryme.top/Article/details/gt2znenhibp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sweek.top/Article/details/gt2ewtghans.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2qatnitix.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gt2eqzupxmg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gt2kaqkgphg.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gt2tnshhqeu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2gicaiixo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2koeizbss.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifvbqhsl.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2psigdycr.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gt2euwzpkcy.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gt2hobaiymb.html

set -euo pipefail
来源：http://dali.sysykeji.top/Article/details/gt2ffjetyvc.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gt2ovpiafww.html

name="Tom"; echo "$name"
来源：http://dali.quarkkingdee.top/Article/details/gt2dqtnyjfi.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gt2gswlslev.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gt2dhoengeb.html

[R04] 位置参数
来源：http://dali.guowangkeji.top/Article/details/gt2rbarufvz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gt2lxtprvah.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gt2sxctldnl.html

name="${1:-default}"
来源：http://dali.jqgfzy.top/Article/details/gt2atulofqw.html

[R06] 判断命令是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2hdzaqfvg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gt2fdcdemeu.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gt2kzqeqwlc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2hggkqekp.html

[R08] 数值比较
来源：http://dali.gzhubu.top/Article/details/gt2whattmhd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnhujegv.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gt2cixwyxli.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gt2aotievmf.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2jboahzmj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gt2lpumsadq.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gt2odnifusz.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gt2svjnnjgg.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gt2eiehumgq.html

stop)  echo "停止" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xcybxhzn.html

*)     echo "未知命令" ;;
来源：http://dali.dianchejie.cn/Article/details/gt2bnznawfa.html

esac
来源：http://dali.jiagoushi.top/Article/details/gt2pgulyipa.html

[R12] for 遍历文件
来源：http://dali.jianghu66.top/Article/details/gt2scxkgqxo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2xtaeqluw.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gt2dudayhpr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2biihfqqe.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gt2ggijsfai.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gt2yfctclkt.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gt2odngyecw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gt2intsqgvn.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gt2jwmbtyzz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gt2qqvshfgv.html

[R17] 数组定义与取值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwdswira.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gt2zbzjeaqq.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwueqcoq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2ycpxvxeo.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2ufmkxytb.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gt2fhpubmoq.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gt2aohkfujg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gt2vvdzbavh.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2fauthjof.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gt2ydrmujrs.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gt2qvgxjsqm.html

echo "${s:0:5}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtkivptu.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gt2xpoxqaot.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shuidangran.top/Article/details/gt2qiqlqfzz.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gt2rhrzoqgc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gt2cyfbidiu.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gt2wvzpjanh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tianlin.xyz/Article/details/gt2vqaecnpt.html

[R26] 命令替换
来源：http://dali.cqqwz.cn/Article/details/gt2cosvkueu.html

now=$(date +%F); echo "$now"
来源：http://dali.jlsjyb.cn/Article/details/gt2ozrcsjfz.html

[R27] 算术展开
来源：http://dali.yanxiufei.cn/Article/details/gt2zhwocsjl.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gt2wbhiujme.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gt2gtzmvork.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqxfdyef.html

[R29] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqletzmz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gt2aacledtc.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gt2qgvfwamx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nwbrower.top/Article/details/gt2aftxfygi.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjyocbin.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gt2obhmdymt.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gt2djluikjw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2lnqrrhkt.html

[R33] 捕获错误并提示行号
来源：http://dali.zycfv.cn/Article/details/gt2ynbmcygh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gt2xliqypyy.html

[R34] 退出时清理
来源：http://dali.haohaochexian.top/Article/details/gt2wicfsmne.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gt2dhyructl.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gt2kyqeamiz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gt2kfkmrhum.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gt2vsxowqbn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gt2dznqfbyt.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fdgmrbnb.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gt2hskkgbyj.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gt2jrfisppf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.birdmap.top/Article/details/gt2aevxxvys.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gt2exaomnyr.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2uzbtbolg.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tztpfyit.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmysldkf.html

[R41] 丢弃输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2akmgavur.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gt2euhgnoir.html

[R42] 输入重定向
来源：http://dali.svipenyu.cn/Article/details/gt2zuhwxwcb.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gt2ieftffph.html

[R43] 按名字查找文件
来源：http://dali.yj20258888.top/Article/details/gt2hqqpjmnc.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gt2hccghluw.html

[R44] 按修改时间查找
来源：http://dali.quarkkingdee.top/Article/details/gt2mzwvoxhb.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gt2dykrblml.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gt2orxydvgz.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gt2zfowdkxe.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gt2fktxzwdx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cqqwz.cn/Article/details/gt2owvoelmi.html

[R47] sed 单行替换
来源：http://dali.kuanghao11.cn/Article/details/gt2grnnrugb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2snboegye.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gt2irhkklvn.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfwyzbjf.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gt2oabjkyre.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxinkj.top/Article/details/gt2ydqnghob.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gt2lgvajcbl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2muskpdlw.html

[R51] 排序去重取前几
来源：http://dali.hysaishi.cn/Article/details/gt2dhzkmixc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gt2wycsskdd.html

[R52] 统计行数
来源：http://dali.cqqwz.cn/Article/details/gt2yyzqbtlu.html

wc -l a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2xxgmjfdu.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gt2dzdqcbku.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gt2kfssvsnm.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gt2vdecvhuj.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2plebdmvt.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gt2qflglvbd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.haohaochexian.top/Article/details/gt2tiodssos.html

[R56] 远程拷贝
来源：http://dali.sysykeji.top/Article/details/gt2vswrrsmd.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gt2rivpxpjo.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gt2vkweysco.html

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhhghpsh.html

[R58] 下载文件
来源：http://dali.snrcjt.cn/Article/details/gt2csxbmqky.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gt2edqwpnbq.html

[R59] 发 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2fqtdmvgl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gt2hdiyvknt.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2xowcgwnh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.9152youxi.cn/Article/details/gt2jxvmfgxo.html

[R61] 磁盘占用
来源：http://dali.haohaochexian.top/Article/details/gt2qwenarlc.html

df -h;  du -sh *
来源：http://dali.yj20258.top/Article/details/gt2cabnyaqy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfyogvx.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gt2wwrclhly.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gt2mnoxrjry.html

free -h;  ps aux | grep nginx
来源：http://dali.zhixingplan.top/Article/details/gt2ococayop.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gt2lqkribjn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxinkj.top/Article/details/gt2psdaichm.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gt2mrichirr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gt2vdanzcfh.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gt2tccuyzoy.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gt2akckmgyn.html

[R67] 生成随机十六进制串
来源：http://dali.jiagoushi.top/Article/details/gt2ujrplfel.html

openssl rand -hex 16
来源：http://dali.shuidangran.top/Article/details/gt2diunhrdy.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gt2qgaryqmu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuxming.cn/Article/details/gt2ccypdwah.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gt2uohddxpt.html

head -c 16 /dev/urandom | base64
来源：http://dali.cdnleiting.top/Article/details/gt2swkwnhqf.html

[R70] 时间戳与互转
来源：http://dali.yueranfly.top/Article/details/gt2zngtcrpl.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gt2aolryeih.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2ifwvnidb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gt2qecwxkhw.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gt2zjkniccg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gt2ryexockz.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gt2ygpnrwyg.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gt2vlezlhug.html

[R74] 批量重命名
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffyacxgb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gt2filjlltl.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gt2ijdcftxd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gt2unqvraxt.html

[R76] 使用临时文件
来源：http://dali.9152youxi.cn/Article/details/gt2fyxoydsb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gt2wvypxavc.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gt2weahjuxk.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gt2wnwgunwk.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gt2jkqembrt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gt2lbcskujd.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gt2nezcsmte.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gt2ulpzzsjz.html

[R80] 查看脚本执行耗时
来源：http://dali.daxiang520.top/Article/details/gt2gspckatn.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gt2hbvifgmo.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2laystrtf.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifyyleoi.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2kyhuwemp.html

[S01] C：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2xafbfbzn.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gt2qikvsiln.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gt2bjzsygnw.html

[S02] C：变量与格式化输出
来源：http://dali.chenzaomai.com/Article/details/gt2eqnnrsxw.html

int a = 10; printf("%d\n", a);
来源：http://dali.fzhhl.top/Article/details/gt2kfxnjuys.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzieeycz.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gt2agqfedtz.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gt2apddzvib.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gt2svoxfdrt.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gt2lyiuwcdq.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gt2mlizzcip.html

[S06] C：字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gt2mlucwfxl.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oaooglrq.html

[S07] C：数组遍历求和
来源：http://dali.xylfe.cn/Article/details/gt2qiklapbf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gt2eoukpmzk.html

[S08] C：动态内存分配与释放
来源：http://dali.pycfn.com/Article/details/gt2oxkiculz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gt2kkbjsrhr.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gt2rmigatyp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gt2odmlvjyo.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gt2kcnezkum.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gt2lyjdmunq.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2uyfanflp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ecnghtot.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gt2hselytth.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2cbqdnljd.html

[S12] C：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmlvjuyq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gt2njkutrjq.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gt2ecguoequ.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangdashe.top/Article/details/gt2mnxhdbqq.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gt2qsxfpcka.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cucudq.cn/Article/details/gt2qasjecyn.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gt2ieyilssd.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gt2lmcsaxaz.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gt2hgbavejy.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gt2vqgsqomz.html

[S17] C：安全拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2azjebqub.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snoslrix.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gt2isrkonmu.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gt2wwidwumt.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gt2hidsnfir.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gt2srxglxgr.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gt2hnhpwtyi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gt2phwbfrip.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gt2pbgtudhq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gt2phalbcok.html

[S22] C：字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gt2gayavjch.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gt2sabypbno.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gt2yyyjahuk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gt2ndzdzgjl.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srhughoa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sysykeji.top/Article/details/gt2yevxrpgd.html

[S25] C：内存拷贝
来源：http://dali.snrcjt.cn/Article/details/gt2xqvjmnpv.html

memcpy(dst, src, n);
来源：http://dali.yonumen.top/Article/details/gt2fpgcdmtk.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gt2algfkmua.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gt2sqplcksk.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gt2xsgzdklw.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2ktdnksfm.html

[S28] C：静态变量
来源：http://dali.cashguo.top/Article/details/gt2zqtenxmf.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgqpijnm.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gt2txdertfc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gt2lpfxnepd.html

[S30] C：头文件保护
来源：http://dali.zycfv.cn/Article/details/gt2sbspnvwy.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gt2nmkmidie.html

#define X_H
来源：http://dali.tianlin.xyz/Article/details/gt2qabmdjrq.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gt2drmgbjgg.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aubgdbdu.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gt2mxwjnkya.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvdwizqx.html

[S32] C++：字符串
来源：http://dali.9152youxi.cn/Article/details/gt2vzadbtbg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okyanhiw.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gt2vivpjaja.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gt2jqlgdwtd.html

[S34] C++：遍历 vector
来源：http://dali.tianlin.xyz/Article/details/gt2euubsulk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gt2yvtbejaz.html


<!-- 参考信息 -->