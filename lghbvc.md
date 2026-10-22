代发 wailian999

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gt2xkpmhpyk.html

ROLLBACK;
来源：http://dali.yangfankeji.com/Article/details/gt2lczrjhqn.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gt2xluihmmf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gt2ifjcgtwc.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awxfwbmo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gt2atnnlhjt.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gt2xdxgxxpp.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gt2axpppkuf.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gt2tqkdemnr.html

[Q69] 查看执行计划
来源：http://dali.wangdashe.top/Article/details/gt2kwalvfep.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gt2pupbocpa.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gt2jkqemolq.html

ANALYZE TABLE users;
来源：http://dali.cucudq.cn/Article/details/gt2fdmrsibo.html

[Q71] 查看建表语句
来源：http://dali.gogol.net.cn/Article/details/gt2iputqlgo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gt2veflcxuk.html

[Q72] 查看索引
来源：http://dali.daria6918.cn/Article/details/gt2jlfmdque.html

SHOW INDEX FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2xewxbccw.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gt2bzkwkrxk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pycfn.com/Article/details/gt2tctzafxm.html

[Q74] 强制使用索引
来源：http://dali.zhixingplan.top/Article/details/gt2wdbocsei.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ybcxt.top/Article/details/gt2yyujwewr.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gt2aazihlgl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pxonxrkv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgfzy.top/Article/details/gt2rzmgceyd.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gt2tzxrbjtg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gt2yhqtcwvi.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gt2vfjjxybx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gt2ptkslsdr.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lyhkxmkd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gt2jgcszsmp.html

[Q79] 字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxtgeuyk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gt2fvgvoonp.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gt2djkoozzm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chbtsftm.html

[Q81] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gt2nsbtidtw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2htfwczkx.html

[Q82] 字符长度与字节长度
来源：http://dali.nwbrower.top/Article/details/gt2lzcsdrdm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2cgdcyaox.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2bmzgzghs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2fjpfdpmc.html

[Q84] 去除首尾空格
来源：http://dali.wangshuangyany.cn/Article/details/gt2qyeolkwu.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjiahcvd.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gt2qhgauiqj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gt2bvxhxxcn.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gt2rxutfidb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gt2skjsalnk.html

[Q87] JSON 字段做条件
来源：http://dali.0kj1m.cn/Article/details/gt2gsqcjtou.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gt2ttkfxpma.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rutfiqbd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.c1oappe.top/Article/details/gt2gpuhkvxn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2fxlnjtdg.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2ewmuhnpn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gt2vpkpnsve.html

[Q90] 生成序号列
来源：http://dali.gotoacloud.top/Article/details/gt2yyurgifn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gt2xcrfeuma.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2uaycnjku.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gt2pgwanmei.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2wqqqrjdj.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrdpoaat.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gt2ckvybhsd.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gt2ybxwrvow.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gt2jzriwrir.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gt2ejuznrmh.html

[R03] 只读变量
来源：http://dali.sweek.top/Article/details/gt2jwblslbj.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdeytpmp.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gt2jvxjlzmp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.haohaochexian.top/Article/details/gt2tqvzgwal.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gt2qfvlvmrc.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gt2telhhqlc.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gt2cgbqxqex.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdjlybrs.html

[R07] if 判断文件
来源：http://dali.hnxiangtu.top/Article/details/gt2ydqdjnvx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guannengcc.top/Article/details/gt2gtyoxgfm.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gt2wmuzotjd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2exubtnxf.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2qrhtsrtn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2tvykiwip.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gt2elspwuwv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2fcunhmtj.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gt2pxkidfmo.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gt2uwjfyakj.html

start) echo "启动" ;;
来源：http://dali.hfpthk.cn/Article/details/gt2ueqxamyv.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gt2rrfonazo.html

*)     echo "未知命令" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gt2mskebdwr.html

esac
来源：http://dali.9152youxi.cn/Article/details/gt2nrqnpeim.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gt2ojjqxxda.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gogol.net.cn/Article/details/gt2zbmvvdxc.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gt2blwkdlod.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gt2dmsifwln.html

[R14] C 风格 for
来源：http://dali.ydzc1.top/Article/details/gt2sdfydttl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gt2perrzgar.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2dxguwmvs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gt2kwoxqdbl.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gt2mvsuwfer.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gt2cjkgjynu.html

[R17] 数组定义与取值
来源：http://dali.xuanzx.com/Article/details/gt2birglsob.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxuanxn.top/Article/details/gt2hucbppgk.html

[R18] 遍历数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2arzqytwq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2frlmmfvt.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gt2inmvbfpi.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wtzhtmgb.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gt2xdpdduby.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guowangkeji.top/Article/details/gt2myimscuc.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gt2hsqefkvf.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gt2ewczhwhb.html

[R22] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gt2zeigdlbv.html

echo "${s:0:5}"
来源：http://dali.snrcjt.cn/Article/details/gt2oxymybsn.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gt2cnmbyjbm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gt2rmtglutj.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gt2lyyhyoqa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gt2erbbkprr.html

[R25] 去后缀 / 去前缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2dcuabqfo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gt2bshtmqsh.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gt2lkpwilge.html

now=$(date +%F); echo "$now"
来源：http://dali.yvedp.cn/Article/details/gt2vtiatarw.html

[R27] 算术展开
来源：http://dali.snrcjt.cn/Article/details/gt2ttnhster.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gt2jntephwm.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gt2afoekfjc.html

echo "scale=2; 10/3" | bc
来源：http://dali.ybcxt.top/Article/details/gt2nrwqsyho.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2xzsfstau.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gt2lruwfzml.html

[R30] 函数返回状态码
来源：http://dali.yvedp.cn/Article/details/gt2iskbfwih.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gt2addcygmv.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gt2zknjjort.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gt2loafnjwr.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gt2kfjmwzds.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hickwzbn.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gt2dwfvwqlp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.316326.xyz/Article/details/gt2jitrwwur.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gt2ghxycags.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gt2ryogqzvl.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gt2marmakyp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shuidangran.top/Article/details/gt2gopinyzi.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gt2oomtnudh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gt2tuybjxjp.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gt2fgpflgyp.html

files=$(ls -1)
来源：http://dali.shzxlz.cn/Article/details/gt2bfzvkebn.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gt2muekeqqm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tian-w.cn/Article/details/gt2ylleauxt.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gt2kneiygdr.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqnanrag.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gt2kobcydgx.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gt2vrqcmncm.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbhyhhon.html

cmd >/dev/null 2>&1
来源：http://dali.yj202588.top/Article/details/gt2npewlcon.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gt2ieogkyuf.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gt2osibyyos.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gt2ikspohif.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2jvtcdezo.html

[R44] 按修改时间查找
来源：http://dali.kuanghao11.cn/Article/details/gt2ripgojpk.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gt2lqiuyfiy.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gt2vywyacfw.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gt2isrgbtwn.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gt2dyklrwzt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cawweffe.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gt2ikfoavly.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlgogkrv.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrxadudg.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gt2tvsrcrnt.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gt2vswyrxhn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gt2xkhrkerh.html

[R50] awk 求和
来源：http://dali.hnxiangtu.top/Article/details/gt2pgpztcul.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2gbnbmdza.html

[R51] 排序去重取前几
来源：http://dali.birdmap.top/Article/details/gt2oqaswzup.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gt2xmxcgbfe.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffhpceoc.html

wc -l a.txt
来源：http://dali.pycfn.com/Article/details/gt2bwerhksi.html

[R53] 查看文件头与实时尾
来源：http://dali.hnxiangtu.top/Article/details/gt2rcvqlhgr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gt2kmurfcrt.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gt2yaicpacl.html

diff a.txt b.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2noytinoo.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gt2yqcttuoi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gt2bhwcqoxn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrdsnbn.html

scp file user@host:/path/
来源：http://dali.yj202588.top/Article/details/gt2gdhhbxrl.html

[R57] 远程执行命令
来源：http://dali.daxiang520.top/Article/details/gt2ipgpnncz.html

ssh user@host 'uptime'
来源：http://dali.cucudq.cn/Article/details/gt2ciwvszvt.html

[R58] 下载文件
来源：http://dali.wangdashe.top/Article/details/gt2zmyrqqhj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gt2jqxwahfa.html

[R59] 发 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2wmigyimj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwtvvnsa.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2vrxviaal.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gt2rsivsziv.html

[R61] 磁盘占用
来源：http://dali.fengsongda.top/Article/details/gt2qqyuokup.html

df -h;  du -sh *
来源：http://dali.guowangkeji.top/Article/details/gt2wlcetlfi.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gt2wribwowj.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmhkprmo.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gt2tcqevrta.html

free -h;  ps aux | grep nginx
来源：http://dali.shuidangran.top/Article/details/gt2ihfoavzc.html

[R64] 结束进程
来源：http://dali.yj20258888.top/Article/details/gt2ejclbylb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258.top/Article/details/gt2oegwrjgr.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gt2idlnyjnw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gt2zvxdxklp.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oeloznaf.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gt2vottbuec.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gt2vswrmtre.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gt2nxoywqjp.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gt2ujcnoghb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2bfvszgnj.html

[R69] 生成随机密码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tbraiioh.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gt2dtbkyxbt.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gt2enlhudlk.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gt2ajixpgfb.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gt2ykuzeyvu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yongpay.top/Article/details/gt2squofgsx.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gt2jwtylmob.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gt2rvszzqhg.html

[R73] 分割大日志
来源：http://dali.gotoacloud.top/Article/details/gt2lwaehqxb.html

split -l 1000 big.log part_
来源：http://dali.vqdsnc.cn/Article/details/gt2yagwrrkm.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gt2rvjmdmiw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gt2iwtljkxm.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2vyiqbtwo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gt2dunjnfkb.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gt2ctaseoce.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gt2xbhsinbi.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gt2klhzvvgj.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gt2uhxwmozk.html

[R78] 交互式菜单
来源：http://dali.andypj.xyz/Article/details/gt2mbgvldpa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gt2mdtborth.html

[R79] 解析命令行选项
来源：http://dali.tianlin.xyz/Article/details/gt2opbokrvi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pfvyofyp.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gt2ptmhduam.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gt2cyehdkzo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2bmlhnuab.html

S. C / C++ 专题
来源：http://dali.dashuyun.cn/Article/details/gt2ulqaussb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2qgwmdygi.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2nteabpds.html

#include <stdio.h>
来源：http://dali.xziqi.cn/Article/details/gt2ecjcbjsw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gt2arhlkmct.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gt2gwpmqthg.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gt2azqbzoyk.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gt2wxnseeso.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gt2snkrwpws.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqbvbscx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2zzaraezo.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gt2mrcvgaee.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lieseukv.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2mocgjbwv.html

strcmp(a, b) == 0
来源：http://dali.chenzaomai.com/Article/details/gt2cqajyblt.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gt2jpmbofuq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gt2kduwbquw.html

[S08] C：动态内存分配与释放
来源：http://dali.chenzaomai.com/Article/details/gt2twyajymf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gt2fbwcrdqj.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gt2jspsmqbz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gt2mlhelmin.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lyosthaf.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gt2oazoqrzs.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2fmvdpnzf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gt2uaixqmrp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqhgtyso.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gt2ecbjaygy.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gt2nemtmwbt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuxming.cn/Article/details/gt2cmzbgxto.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gt2dffeaxlt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gt2klxcvimo.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2xvviqblz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gt2nqsyfgbo.html

[S15] C：类型转换
来源：http://dali.zdqjudy.top/Article/details/gt2incjqxhy.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gt2yunnecqv.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gt2rgdlxonj.html

x |= (1 << 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2acrumlqi.html

[S17] C：安全拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2keehglxe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gt2qnzulakz.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gt2wsltuvqn.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gt2stkvtvgq.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2zeiphxnt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2hgunjpsq.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gt2fvmazwjz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gt2qxuwnskg.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcdlefsk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gt2fzcoobqx.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gt2bingjnar.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svueuwir.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gt2nseyglwm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gt2ldpavnjv.html

[S24] C：获取本地时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgmuojsi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxexhavx.html

[S25] C：内存拷贝
来源：http://dali.tian-w.cn/Article/details/gt2bpcaxzpj.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gt2nfmgkhji.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gt2mnurhuca.html

memset(a, 0, sizeof a);
来源：http://dali.tanke756.top/Article/details/gt2fkyhcbbn.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gt2ptiybbus.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2ufbaoyor.html

[S28] C：静态变量
来源：http://dali.xinyue.icu/Article/details/gt2rkgioejy.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gt2opqlthjt.html

[S29] C：变参函数
来源：http://dali.gaohongyu789.top/Article/details/gt2lgyvuyuu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gt2qkmshhhm.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gt2szqwigqq.html

#ifndef X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elcacvyn.html

#define X_H
来源：http://dali.meibo888.top/Article/details/gt2rzufglwq.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gt2hecdrisw.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2tdvvnenm.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gt2qashyusn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2skwteyqk.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gt2ukwshsrg.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gt2otqhtjrk.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gt2txljyjis.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hywenlv.cn/Article/details/gt2giypeqyh.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gt2khnzgzvz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtpyqlty.html


<!-- 参考信息 -->