代发 wailian999

[Q78] 当前时间
来源：http://dali.jyoumei.cn/Article/details/gtxeopotxt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hfpthk.cn/Article/details/gtrqnxhyms.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtvrztapja.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gtfkeppzca.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmuapyti.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtgzvxuykn.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtzllsgfnp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sweek.top/Article/details/gtkzfwvgvo.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gtpjgxrjia.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtfhmxbqcs.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtpftcruts.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtmkvhxqnm.html

[Q84] 去除首尾空格
来源：http://dali.gogol.net.cn/Article/details/gtpgbdcfrc.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtjnlazibu.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gtjkzcirhd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gtgdwtqrww.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigfzy.top/Article/details/gtmjdguutk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gtitepkoht.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gthgwhfiuu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtelbjwrca.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtdxjtjntn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yangfankeji.com/Article/details/gttjryfijg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtehfvlvtr.html

[Q89] 判断表是否存在
来源：http://dali.birdmap.top/Article/details/gtyxturrgb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hfpthk.cn/Article/details/gtoxlzcrpg.html

[Q90] 生成序号列
来源：http://dali.sxryk.cn/Article/details/gtyhvxuaer.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gtmxoidbka.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthefoujmc.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtgmwxvtlg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwptuhdtl.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gtplcsjeew.html

#!/usr/bin/env bash
来源：http://dali.jianghu66.top/Article/details/gtlfbzlqrq.html

set -euo pipefail
来源：http://dali.chenlongwang.top/Article/details/gtazdpgpon.html

[R02] 变量赋值与使用
来源：http://dali.sweek.top/Article/details/gtfmpsifqj.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gtnoqyxfvi.html

[R03] 只读变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatmwwxpw.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gtyhbtimcv.html

[R04] 位置参数
来源：http://dali.sxryk.cn/Article/details/gtzezeljwb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gtjigkjfhn.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gtkhmevcio.html

name="${1:-default}"
来源：http://dali.yj202588.top/Article/details/gtosxauqhk.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gtkitqulwp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtjiocaxxl.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gtqvwnhngd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gtkvwhmpza.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gtshvsoyuz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ybcxt.top/Article/details/gtgnfhawbe.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gtzvwujtfn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gtpyktvkei.html

[R10] 正则匹配
来源：http://dali.yongpay.top/Article/details/gtzkgktaup.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tianlin.xyz/Article/details/gtgxfsjwro.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gtmxnlzqns.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gtsgusxpii.html

start) echo "启动" ;;
来源：http://dali.gotoacloud.top/Article/details/gtkzbvveav.html

stop)  echo "停止" ;;
来源：http://dali.shuidangran.top/Article/details/gtguacdepg.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gtvbqdsenw.html

esac
来源：http://dali.hongshengwenyu.top/Article/details/gtjwfkcbpv.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gtqwshbsxr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gtdzcytdps.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtvmefobav.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtetglxibl.html

[R14] C 风格 for
来源：http://dali.cucudq.cn/Article/details/gtncbizlui.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtwyfervdg.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gteycdjybo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sweek.top/Article/details/gtgziqtxzz.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gtebyuzpas.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtxksmjztx.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gtbwsjvnve.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gtsynuluoj.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gtyrqyiisa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gtibvvbvay.html

[R19] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtspfqzyub.html

echo "${#arr[@]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtaaqxdxeq.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gttnsvhldp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gtosgnzzpr.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtsjpbyeft.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gtrwbkpojw.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtyfuitxyv.html

echo "${s:0:5}"
来源：http://dali.vqdsnc.cn/Article/details/gtpqxrxtog.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtxruyayte.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gtcnvexnmq.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtugnodcvj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gtzclinsgb.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenzaomai.com/Article/details/gtcjdfwpxo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gtjidpnhwv.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gtwjnuohxm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhixingplan.top/Article/details/gtwessibsf.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gtkgdjmaef.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gtmncnrkyd.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gtrbqdhdpe.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gtshaxkdfo.html

[R29] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtendzvanr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tianlin.xyz/Article/details/gtgekbmiuk.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtufbalqlt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjccotzz.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtgzrjucpg.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbxephast.html

[R32] 参数个数校验
来源：http://dali.jinqigufen.top/Article/details/gtoffqjwvw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gttpiutlmt.html

[R33] 捕获错误并提示行号
来源：http://dali.gogol.net.cn/Article/details/gtoyvtwqbl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgfzy.top/Article/details/gttegjbvmm.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtgnqdtkyj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtwlcktawu.html

[R35] 后台执行并等待
来源：http://dali.0kj1m.cn/Article/details/gtxoqkfhae.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gtkoceluxq.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtcfstfnpj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdibxtol.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtngiuatmp.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gtzuyvupgf.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gtkoqurcvb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gtqvbkiobk.html

[R39] 重定向标准输出与错误
来源：http://dali.xuanzx.com/Article/details/gthochkcgi.html

cmd > out.log 2>&1
来源：http://dali.xylfe.cn/Article/details/gtwfbwrzju.html

[R40] 追加写日志
来源：http://dali.xziqi.cn/Article/details/gtauvzexus.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gtnhrshurj.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gttgbygnlu.html

cmd >/dev/null 2>&1
来源：http://dali.zycfv.cn/Article/details/gtrchirtrh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gtiszpfvyh.html

wc -l < a.txt
来源：http://dali.fengsongda.top/Article/details/gtgcxfsfhf.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtwypqajmz.html

find . -name "*.log" -type f
来源：http://dali.sxryk.cn/Article/details/gtndtbdvte.html

[R44] 按修改时间查找
来源：http://dali.ehwqpu.com/Article/details/gtwolbersd.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gtnrzomunh.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gtfkgaedcm.html

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gtqoudeenl.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gtvorigqht.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cqqwz.cn/Article/details/gtkmlygaxt.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtebabodur.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtwzlrmbuf.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtckkipopt.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtriksjdlj.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gttsaqsuyl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gttycsxkmu.html

[R50] awk 求和
来源：http://dali.zhoulong.xyz/Article/details/gtpzocclgy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtzpdqocda.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gtswhyxwym.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gtznzwgukz.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gtstauhstm.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gttcjryqbq.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gtspghafkn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gtuvwqblmf.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gtomstbjxr.html

diff a.txt b.txt
来源：http://dali.cqqwz.cn/Article/details/gtqzendsue.html

[R55] 压缩与解压
来源：http://dali.feifeiyinyue.top/Article/details/gtvmdfzkyd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gtnixobunc.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelfwelob.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gtswqqwonr.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gttclwubvk.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gtxjbldnks.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gtetmxxkbt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gtmtixeemu.html

[R59] 发 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gthwpvcvna.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtvxrvbvct.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtohgpgiam.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gtxbitupgd.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gtmaseachj.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gtkioxndtc.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gtygcbvjga.html

du -ah . | sort -rh | head -10
来源：http://dali.ydzc1.top/Article/details/gtpwsofteo.html

[R63] 内存与进程
来源：http://dali.pycfn.com/Article/details/gtpdnmwytk.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gtbcrhzdlq.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtcgyquwmk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gtywuiyofj.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gtgzcfdngv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtgbfbnchy.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gtfbwyomst.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gtkfkasxmu.html

[R67] 生成随机十六进制串
来源：http://dali.kuanghao11.cn/Article/details/gtkxsgdlcd.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gtcvqlrnwm.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gtuikxfceu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuxming.cn/Article/details/gtdjdroejc.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gtiacouann.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gtetykjazt.html

[R70] 时间戳与互转
来源：http://dali.cucudq.cn/Article/details/gtbqlnkuaf.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gtgnjnenqi.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtspodzber.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gtxffwvwqz.html

[R72] 等待端口就绪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjljcvhgr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtbhhofqkn.html

[R73] 分割大日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhhyprzt.html

split -l 1000 big.log part_
来源：http://dali.zycfv.cn/Article/details/gtcjadugbl.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtqjeghzgc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlaghmqjw.html

[R75] 导出环境变量
来源：http://dali.yonumen.top/Article/details/gtoknhnfpt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gthridpsho.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gtzmjmvblc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtuyabcxvf.html

[R77] 读取用户输入
来源：http://dali.hammf.cn/Article/details/gtrukkwfvt.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gthiczmwaz.html

[R78] 交互式菜单
来源：http://dali.yueranfly.top/Article/details/gtjmtoxmtj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhixingplan.top/Article/details/gtqtpbxdum.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gtrflhuifj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gtzqpjeoln.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gtlsrdmjhr.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gtudlivnyf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtihktegla.html

S. C / C++ 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtpdmferwy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolnjhnka.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtwjifcuqm.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gtajilpqan.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhengqikj.top/Article/details/gtwzhcrcjo.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gtrngcgxxf.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gtlgfgvloa.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gtdqrbknzq.html

int x; scanf("%d", &x);
来源：http://dali.zhixingplan.top/Article/details/gtmcucuvvz.html

[S04] C：字符串复制
来源：http://dali.xuanzx.com/Article/details/gtjceupacb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gtjnrinsvd.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtclfvvqmi.html

strlen(s)
来源：http://dali.ppjwa.cn/Article/details/gtrstlrtqc.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gtwtyurpru.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtxdrvkxtx.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gtuvemobxp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gtwnognrjx.html

[S08] C：动态内存分配与释放
来源：http://dali.cheryme.top/Article/details/gtpvjvwviq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gtdqbksmcm.html

[S09] C：结构体定义与初始化
来源：http://dali.hnqzz.top/Article/details/gtuthomsnn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ppjwa.cn/Article/details/gtwgozaiip.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gtpkbirmfb.html

int *p = &a;  *p = 5;
来源：http://dali.meibo888.top/Article/details/gtojrkdbvj.html

[S11] C：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtibhajues.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gtmwtruzgk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gtgotridwk.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gthgkycwgs.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gtdckqsfaf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtzxtvedke.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gtnhtekamo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gtfqpqpouc.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gtkqnbezzi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.kuanghao11.cn/Article/details/gtxoxqwvkx.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gtnaidxyvc.html

(double) a / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiicnbszr.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gtcgciuztu.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtjxddupxz.html

[S17] C：安全拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtaqwlbtth.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gtouuzbjyg.html

[S18] C：命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtrmzigibu.html

int main(int argc, char **argv)
来源：http://dali.ivvv.top/Article/details/gtdseszaoq.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtiqhbmthi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtsqogbkpw.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtjhgqphwb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtjxinbheo.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gtdjgordiz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gtnebuangj.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gthwnortoa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gthpgqmwdk.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gtjpborovr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gtxljdargp.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gtqwoxrvxw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gtreyeirdx.html

[S25] C：内存拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtbajrzwym.html

memcpy(dst, src, n);
来源：http://dali.jqgfzy.top/Article/details/gttkabftna.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gthetmfror.html

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gtoynokels.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gtzuhhmxne.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtbpudsjgn.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gtkngcivgj.html

static int counter = 0;
来源：http://dali.cheryme.top/Article/details/gtnthwscxa.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gtdjbtbnzv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtkrqkumyb.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gtowjbjowh.html

#ifndef X_H
来源：http://dali.cucudq.cn/Article/details/gtjtwvawkh.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gtrgnpdlfm.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gttjsqcbrj.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtqalyuvdw.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtmkvaqcsk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtifguxqny.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gtzvpofzaf.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gtnbdqdafd.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtlzhkilkb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dianchejie.cn/Article/details/gtmjfdulpv.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gtiqtxagsq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gtiypatpwx.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gtsnmumeoa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gthbnjijrx.html

[S36] C++：unordered_map
来源：http://dali.gaohongyu789.top/Article/details/gtltlcnenn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtqbunsqdh.html

[S37] C++：set
来源：http://dali.dianchejie.cn/Article/details/gtycgiwder.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gthteyrdpi.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqlhmdjy.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtbvfkktbj.html

[S39] C++：自定义比较器排序
来源：http://dali.dashuyun.cn/Article/details/gtfyxskmyt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gtataayboy.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gtrbrfdnvp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hysaishi.cn/Article/details/gtbgnzjfll.html

[S41] C++：类与构造函数
来源：http://dali.svipenyu.cn/Article/details/gtsrpkeuwl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gthtgkqpjj.html

[S42] C++：继承与虚函数
来源：http://dali.jlsjyb.cn/Article/details/gtylmbfdoi.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuxming.cn/Article/details/gtjtgxzwoy.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gtwpdfwjpu.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gtlcumqcip.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gtvbfriqqa.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqwfrvybq.html

[S45] C++：lambda
来源：http://dali.havefunace.top/Article/details/gtnbdrcseb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xinyue.icu/Article/details/gtvzprezda.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gtjodhzhyp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gtbtdwchtn.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkrwtlhx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyfajfntk.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtvjfdqviw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tianlin.xyz/Article/details/gtkqjmlyoy.html


<!-- 参考信息 -->