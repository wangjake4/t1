代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gt2nttiaxar.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gt2loxzpmdt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zdqjudy.top/Article/details/gt2xsmngyad.html

[Q70] 更新统计信息
来源：http://dali.zhongyouzk.top/Article/details/gt2wndeyuru.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gt2jbozpkzm.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gt2ygvjnivp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gt2nwepvrtp.html

[Q72] 查看索引
来源：http://dali.iojbl.cn/Article/details/gt2rexulrpx.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2samohphf.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gt2todkinpz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuxming.cn/Article/details/gt2hedrqglb.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gt2wigbfsjo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gt2ugztdhje.html

[Q75] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2pnicqlze.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2efbjrnxj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shangyingyoupin.top/Article/details/gt2ngzaivmq.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gt2eirniqta.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywyobzxk.html

[Q77] 时间加减
来源：http://dali.chenlongwang.top/Article/details/gt2qrxsxjwn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gt2hjphvpvi.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gt2bvyhplll.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gotoacloud.top/Article/details/gt2fwjlqelf.html

[Q79] 字符串拼接
来源：http://dali.fzhhl.top/Article/details/gt2gmcqdtsx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dianchejie.cn/Article/details/gt2fvgxezbt.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gt2ejptcqkz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqnbqkcd.html

[Q81] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gt2gguymofw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2rzwtrflq.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gt2bscdgrql.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2jdadspmh.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gt2ywfbyody.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2xlqehkpa.html

[Q84] 去除首尾空格
来源：http://dali.dashuyun.cn/Article/details/gt2tltkavrk.html

SELECT TRIM(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2kfmkqiqc.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gt2oxmnecai.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jiagoushi.top/Article/details/gt2pcvfuofy.html

[Q86] 读取 JSON 字段
来源：http://dali.ppjwa.cn/Article/details/gt2xitmofzr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cashguo.top/Article/details/gt2bsxgumaq.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gt2bdvqxofa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yanxiufei.cn/Article/details/gt2zjmolskv.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gt2xwnrbsfu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gt2mjgkexxy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.316326.xyz/Article/details/gt2iiktowbs.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gt2ssbroicm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gt2sivprwsg.html

[Q90] 生成序号列
来源：http://dali.aizwys.cn/Article/details/gt2sflncrwl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gt2addhirdl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2gsdogfkx.html

R. Bash 专题
来源：http://dali.kuanghao11.cn/Article/details/gt2txotqrrf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2mtxddbgf.html

[R01] shebang 与严格模式
来源：http://dali.jlsjyb.cn/Article/details/gt2ybokwndr.html

#!/usr/bin/env bash
来源：http://dali.sufxvd.cn/Article/details/gt2jagmzqwl.html

set -euo pipefail
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2orsccnpf.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gt2heivogiz.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gt2kffxcuqq.html

[R03] 只读变量
来源：http://dali.nwbrower.top/Article/details/gt2ojzexouz.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gt2nozqghod.html

[R04] 位置参数
来源：http://dali.jyoumei.cn/Article/details/gt2skcdqrsd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpwnndw.html

[R05] 参数默认值
来源：http://dali.iojbl.cn/Article/details/gt2owlitduv.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gt2yxerjvpx.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gt2grbxysdn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gt2oniosgwd.html

[R07] if 判断文件
来源：http://dali.xylfe.cn/Article/details/gt2ichpwhtb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gt2ivipkpvy.html

[R08] 数值比较
来源：http://dali.daxiang520.top/Article/details/gt2xoxwgnbj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqmhmmtq.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxnkwoho.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2wtewzkne.html

[R10] 正则匹配
来源：http://dali.xinyue.icu/Article/details/gt2qymorvgh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.iojbl.cn/Article/details/gt2oifcqdps.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gt2jgmrjiqh.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gt2znxceshu.html

start) echo "启动" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2hrjgjkss.html

stop)  echo "停止" ;;
来源：http://dali.dianchejie.cn/Article/details/gt2shoituxw.html

*)     echo "未知命令" ;;
来源：http://dali.daxiang520.top/Article/details/gt2hancpipj.html

esac
来源：http://dali.tian-w.cn/Article/details/gt2ywqhnhrj.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gt2jmvgwsnw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gt2dheqiaww.html

[R13] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2uynmncjb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2duuajprd.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gt2waxjvkpa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gt2hcnooylr.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2sllewfft.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gt2bgyiczgk.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2gsfzabwg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gt2izqjslhu.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gt2vopjehrh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gt2gzyjemrb.html

[R18] 遍历数组
来源：http://dali.pycfn.com/Article/details/gt2mqsfoazt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckjwfjxq.html

[R19] 数组长度
来源：http://dali.jianghu66.top/Article/details/gt2voxcejeo.html

echo "${#arr[@]}"
来源：http://dali.xinyue.icu/Article/details/gt2xqxeudvd.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnchogoh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gt2eyuhfpao.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gt2affpminb.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gt2ogbwtczr.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gt2hbgggcjs.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gt2mrqhobrl.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gt2zsbbnpju.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daria6918.cn/Article/details/gt2exxjfzir.html

[R24] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gt2jgkhgotd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.iojbl.cn/Article/details/gt2qcavkjcj.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gt2ifpxukxk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cheryme.top/Article/details/gt2kzeltpia.html

[R26] 命令替换
来源：http://dali.hfpthk.cn/Article/details/gt2fltkswcc.html

now=$(date +%F); echo "$now"
来源：http://dali.c1oappe.top/Article/details/gt2vidrfyzu.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gt2hwzhnclr.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gt2wgnzvfaz.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gt2odzdrccl.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyzfijjl.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gt2nphymlub.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aibaodan.cn/Article/details/gt2wjesdpri.html

[R30] 函数返回状态码
来源：http://dali.redwolf501.top/Article/details/gt2iayaeaiz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gt2kacjgtoj.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gt2ukijkeha.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ddpgrmfg.html

[R32] 参数个数校验
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyftqxfg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gt2hudhyqev.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gt2arletgnj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxinkj.top/Article/details/gt2uhxixwiy.html

[R34] 退出时清理
来源：http://dali.zhengqikj.top/Article/details/gt2mbpxnage.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gt2ypwgcayc.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gt2vjzvuuor.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gt2mgmwcajz.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gt2tijpvogu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cugpbwcd.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgtkjuim.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gt2urfsrbnz.html

[R38] 管道串联
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ihltgopp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hywenlv.cn/Article/details/gt2vpuveutd.html

[R39] 重定向标准输出与错误
来源：http://dali.chenlongwang.top/Article/details/gt2rffrpmcv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzwiqqd.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gt2domfrwlk.html

echo "log" >> out.log
来源：http://dali.dianchejie.cn/Article/details/gt2coddfenn.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gt2wrvetazc.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2wfwzvrix.html

[R42] 输入重定向
来源：http://dali.vqdsnc.cn/Article/details/gt2fzswxqhj.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gt2kaazlfvq.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqahrajx.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gt2ghgjklyn.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gt2ewdfhrii.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gt2cogjllba.html

[R45] 批量删除
来源：http://dali.nanxuanxn.top/Article/details/gt2tlxewsmk.html

find . -name "*.tmp" -delete
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbnxsesg.html

[R46] 递归替换文件内容
来源：http://dali.sysykeji.top/Article/details/gt2jyonyjrg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gt2lybgdxcp.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gt2vhrqlhhf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2pdseoopc.html

[R48] awk 取指定列
来源：http://dali.shuidangran.top/Article/details/gt2habarucd.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2ckxpcxwy.html

[R49] awk 带条件
来源：http://dali.jianghu66.top/Article/details/gt2czdeokux.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guowangkeji.top/Article/details/gt2qpgrxprf.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gt2kqpdsbfw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2nwfxlejw.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gt2moxkrczz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tianlin.xyz/Article/details/gt2eovjerlt.html

[R52] 统计行数
来源：http://dali.birdmap.top/Article/details/gt2jxgozwij.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gt2yaaletui.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gt2ecdeegoj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuetiantiany.cn/Article/details/gt2fztcppgb.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gt2yjgvntmp.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hwxvncsd.html

[R55] 压缩与解压
来源：http://dali.haohaochexian.top/Article/details/gt2hvgrlrzn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gt2uskzactb.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gt2iucdchbi.html

scp file user@host:/path/
来源：http://dali.fengsongda.top/Article/details/gt2omcpydwc.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gt2xnoyubmd.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gt2hzkkwfkh.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gt2dbrcpvrt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yangfankeji.com/Article/details/gt2acascnnf.html

[R59] 发 POST JSON
来源：http://dali.havefunace.top/Article/details/gt2uxaahtqo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sysykeji.top/Article/details/gt2vyhephpo.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gt2lypyjwmy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cheryme.top/Article/details/gt2albtgqnb.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gt2ozahzvqc.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gt2sqklmwni.html

[R62] 找最占空间的文件
来源：http://dali.wangdashe.top/Article/details/gt2aowbsncn.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gt2fezfahrk.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gt2cajpitys.html

free -h;  ps aux | grep nginx
来源：http://dali.fengsongda.top/Article/details/gt2cnxnxaqp.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cockxvdv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ppjwa.cn/Article/details/gt2pgxqmjmm.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gt2dgqddjwe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gt2qrqgcham.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gt2tvxfuhex.html

crontab -e;  crontab -l
来源：http://dali.dianchejie.cn/Article/details/gt2basjyooh.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gt2kzcpubrp.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gt2ygidxdzg.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gt2mpzxroai.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gt2iezrcbkk.html

[R69] 生成随机密码
来源：http://dali.nanxinkj.top/Article/details/gt2koyrjsih.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenzaomai.com/Article/details/gt2yxfjldmw.html

[R70] 时间戳与互转
来源：http://dali.nanxinkj.top/Article/details/gt2mlxnqesz.html

date +%s;  date -d @1700000000
来源：http://dali.xuanzx.com/Article/details/gt2dsbmrupo.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gt2znibmvdr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gt2upwojzoh.html

[R72] 等待端口就绪
来源：http://dali.tanke756.top/Article/details/gt2eiautcox.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gt2tgtoicxm.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gt2zmjoivfn.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gt2qxzuhlho.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gt2rnkrfijy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gt2xuwapvre.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2abenkhxd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gt2exojwvch.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2vlojcfrc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gt2zzvtcmso.html

[R77] 读取用户输入
来源：http://dali.haohaochexian.top/Article/details/gt2bjlnludk.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gt2claapqcu.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ekhqteyd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gt2ikibqwhg.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gt2lgcynmqt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2nodccamj.html

[R80] 查看脚本执行耗时
来源：http://dali.316326.xyz/Article/details/gt2lyyacptu.html

time ./run.sh
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkkzaaoo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2rxqtbjud.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2rllthdxn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ttqptieg.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2ywpopife.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gt2fdappydm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ofwwbpji.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gt2bnoornft.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ecwbhtbg.html

[S03] C：读入整数
来源：http://dali.zycfv.cn/Article/details/gt2qosjjtdk.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttgofphx.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gt2srgfgspb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gt2dhagbwty.html

[S05] C：字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2laufwjlm.html

strlen(s)
来源：http://dali.nanxinkj.top/Article/details/gt2msobvzjy.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gt2mzulyhni.html

strcmp(a, b) == 0
来源：http://dali.hnqzz.top/Article/details/gt2jntayisa.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gt2aqgirhdv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gt2cmvpwwvo.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gt2ozdakwze.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gt2qobqgdtq.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gt2ximeyjwm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yvedp.cn/Article/details/gt2izqcbycm.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwjbbdxy.html

int *p = &a;  *p = 5;
来源：http://dali.jyoumei.cn/Article/details/gt2jokkkerv.html

[S11] C：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2mjckfblp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gt2ggdwusjr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2awplzmib.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gt2nnjnkvaf.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gt2rslcuztz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gt2flvjhfxu.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gt2xllstwcx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gt2rofhjark.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gt2apyzggos.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gt2ekpykeev.html

[S15] C：类型转换
来源：http://dali.gzhubu.top/Article/details/gt2yvgcxvct.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gt2fbdzblav.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqklvedq.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxkdxugk.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gt2djdyrmcj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gt2mkbpdmsm.html

[S18] C：命令行参数
来源：http://dali.sxryk.cn/Article/details/gt2atsutctm.html

int main(int argc, char **argv)
来源：http://dali.andypj.xyz/Article/details/gt2kwcfnjom.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gt2ceexpghb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdqneqdt.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gt2vjdovaxl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gt2oxppkkmu.html

[S21] C：字符类别判断
来源：http://dali.yanxiufei.cn/Article/details/gt2uvsuptec.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.snrcjt.cn/Article/details/gt2tleckawu.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gt2yhwmikty.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jiagoushi.top/Article/details/gt2ogxzxmei.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gt2mgftwonx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gt2axawelbi.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gt2jfsfszpe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gt2bvfwdorw.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gt2jtldmzto.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gt2tlbdfacf.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gt2yzrhsubv.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gt2mhndkoob.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2uzukggrz.html

const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2txohdpyv.html

[S28] C：静态变量
来源：http://dali.hnxiangtu.top/Article/details/gt2nbljagjj.html

static int counter = 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oalowjrw.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gt2ittpqxel.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gt2dnlabjct.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gt2reolonft.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gt2wiarzljg.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gt2hliubyis.html

#endif
来源：http://dali.smart0.xyz/Article/details/gt2tanldfnd.html

[S31] C++：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbbxqpsg.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odlhvamq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gt2smnarekh.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gt2wsswwijm.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gt2pgzatubt.html

[S33] C++：vector 增删
来源：http://dali.xinyue.icu/Article/details/gt2lizahqzc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gt2quxeqnwx.html

[S34] C++：遍历 vector
来源：http://dali.redwolf501.top/Article/details/gt2uizkfuve.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gt2xwesquoe.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gt2ccbqbnwp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2xdttkgfo.html

[S36] C++：unordered_map
来源：http://dali.daria6918.cn/Article/details/gt2ulqnwfts.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2tpqybzgo.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gt2lebuauus.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jianghu66.top/Article/details/gt2edhpkprf.html

[S38] C++：排序
来源：http://dali.hnqzz.top/Article/details/gt2mezgkaep.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gt2duaxpwdm.html


<!-- 参考信息 -->