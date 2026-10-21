代发 wailian999

[Q78] 当前时间
来源：http://dali.fzhhl.top/Article/details/gtnpkhlngt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gtralavzll.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gtplmeaijv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gttstvbtwb.html

[Q80] 字符串截取
来源：http://dali.yuxming.cn/Article/details/gtzxrqspee.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cheryme.top/Article/details/gtlgymwxtf.html

[Q81] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtedbshepg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvfyoopm.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gtfynawbwp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtkxsaiiwr.html

[Q83] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtatkjdazr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtoyoyavyg.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gtukpkcdfo.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtbtwjgner.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gtvxtpraxp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.smart0.xyz/Article/details/gtfvmecqcu.html

[Q86] 读取 JSON 字段
来源：http://dali.bjfxy.top/Article/details/gtecxstfxk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gtqloifwfg.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtocxfowpv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtyhqgfukx.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoggrycnq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhengqikj.top/Article/details/gtqiubkriq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.316326.xyz/Article/details/gtoblshvxj.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gtcaicbppn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtgleapemk.html

[Q90] 生成序号列
来源：http://dali.daria6918.cn/Article/details/gteanjkbig.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoveiblqb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtatkmgamx.html

R. Bash 专题
来源：http://dali.guowangkeji.top/Article/details/gtvwtetwzb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gttrntrxcg.html

[R01] shebang 与严格模式
来源：http://dali.jqgufenzy.top/Article/details/gtxdiajyug.html

#!/usr/bin/env bash
来源：http://dali.gotoacloud.top/Article/details/gteotizfby.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gtuknrrlzx.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gtgzvmdylj.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gtgupdvtan.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gtoexxyamp.html

readonly PI=3.14
来源：http://dali.jqgfzy.top/Article/details/gtfgqilxbt.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gtnanizglr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gtwzekkcpa.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gttgdzinvt.html

name="${1:-default}"
来源：http://dali.yangfankeji.com/Article/details/gteficsnli.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gthizeyldf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtyvtmxrzm.html

[R07] if 判断文件
来源：http://dali.andypj.xyz/Article/details/gtntyqzwde.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guannengcc.top/Article/details/gtzxbiacyz.html

[R08] 数值比较
来源：http://dali.yuanzhike.top/Article/details/gtisvmloue.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqftyahj.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtqsbwngsc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.bjfxy.top/Article/details/gtcfqphhws.html

[R10] 正则匹配
来源：http://dali.aibaodan.cn/Article/details/gtxdzwxqik.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gtszilkidb.html

[R11] case 多分支
来源：http://dali.0kj1m.cn/Article/details/gtenmtednm.html

case "$1" in
来源：http://dali.sysykeji.top/Article/details/gtstlqbtwq.html

start) echo "启动" ;;
来源：http://dali.yongpay.top/Article/details/gtcabwymnl.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtorxitvuw.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gtahvofiqh.html

esac
来源：http://dali.hammf.cn/Article/details/gtcooulhur.html

[R12] for 遍历文件
来源：http://dali.shangyingyoupin.top/Article/details/gtgslfmusf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daxiang520.top/Article/details/gtocqaufla.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gtzzfdwzkp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtpwgrhpdt.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gtixhjxblh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtlylhcivi.html

[R15] while 逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtmjfgvtfx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbrykslc.html

[R16] until 等待条件
来源：http://dali.jinqigufen.top/Article/details/gtlddxfucz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtvbszltai.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtoprslbni.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gtnjzhnbcr.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gtwmrlofup.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gttwzioynl.html

[R19] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtksvhcsvz.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gtzvsfdomr.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gtbpuwkecz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcissemn.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gtgghuviku.html

echo "${#s}"
来源：http://dali.c1oappe.top/Article/details/gtxysjonxh.html

[R22] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtetpysugh.html

echo "${s:0:5}"
来源：http://dali.daria6918.cn/Article/details/gtiyosxeog.html

[R23] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbcthqmo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gtaytlbbyr.html

[R24] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtwmjshnxl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gtuandfxbn.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gtxroylaef.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgfzy.top/Article/details/gtfbyjtdem.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtsvtcwqwr.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtfmvqycov.html

[R27] 算术展开
来源：http://dali.birdmap.top/Article/details/gtmrmhzqhe.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gtlypwmpma.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gtpgtkghin.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangshuangyany.cn/Article/details/gtwzijjfga.html

[R29] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtrhaesqpw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gtjblgxgch.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtblbfubgt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangdashe.top/Article/details/gteacyiwqq.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gtgwlknnox.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gtubuifbzz.html

[R32] 参数个数校验
来源：http://dali.dianchejie.cn/Article/details/gtzezjxymk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtoaqehhsd.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtomjnjjza.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gtbirtxeza.html

[R34] 退出时清理
来源：http://dali.tian-w.cn/Article/details/gtorfipghs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtrczkxopo.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gtpgqzzrjm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtqlesju.html

[R36] 并发执行多个任务
来源：http://dali.cashguo.top/Article/details/gtlslhaerq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gttprpsjof.html

[R37] 把输出赋给变量
来源：http://dali.shangyingyoupin.top/Article/details/gtfzlsjnec.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gtafoiwoyc.html

[R38] 管道串联
来源：http://dali.jqgufenzy.top/Article/details/gtfnypdssp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gtjelcnwzx.html

[R39] 重定向标准输出与错误
来源：http://dali.hywenlv.cn/Article/details/gtjmxdmtbv.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncvtdjul.html

[R40] 追加写日志
来源：http://dali.sysykeji.top/Article/details/gtspstretq.html

echo "log" >> out.log
来源：http://dali.sxryk.cn/Article/details/gtefwsglej.html

[R41] 丢弃输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtekhxwcia.html

cmd >/dev/null 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtyfhsxqnt.html

[R42] 输入重定向
来源：http://dali.nanxuanxn.top/Article/details/gtjgssoadr.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gtwgdztgsy.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gtdmrptkot.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gtqntsckgz.html

[R44] 按修改时间查找
来源：http://dali.vqdsnc.cn/Article/details/gthaengyln.html

find . -mtime -7 -type f
来源：http://dali.gzhubu.top/Article/details/gthrrukudl.html

[R45] 批量删除
来源：http://dali.jyoumei.cn/Article/details/gtqexveipw.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gtwjxvwvvt.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gtkqgqnpll.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cqqwz.cn/Article/details/gtibjgbsum.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gtbonegnql.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtivecrhaz.html

[R48] awk 取指定列
来源：http://dali.havefunace.top/Article/details/gtiqekmmjf.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtlgwdvknv.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gthcvlydjp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtdjffygpt.html

[R50] awk 求和
来源：http://dali.pycfn.com/Article/details/gthwxwurme.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtsazvhvst.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gtopmddjkp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gtfqpjyjqf.html

[R52] 统计行数
来源：http://dali.vqdsnc.cn/Article/details/gtkjoqtvyw.html

wc -l a.txt
来源：http://dali.zdqjudy.top/Article/details/gtwpsmaxoh.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gtwyravymy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtpwljqtij.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gtfxfjuqhh.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbjenhec.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gtmaadlgkl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.snrcjt.cn/Article/details/gtmlqdlxnq.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtqbipdngd.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtpvylgbak.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gttkumghmm.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gteqoadzrt.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gtjqvswkhp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gtzooazxth.html

[R59] 发 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gthzsxxllo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gthitfjkdn.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtjdzllece.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.0kj1m.cn/Article/details/gtdshptszl.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gthmqdnoyn.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gthbukbala.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtobdnzjdi.html

du -ah . | sort -rh | head -10
来源：http://dali.snrcjt.cn/Article/details/gtdnwtdfag.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gtetvhbmcn.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gtectveqxm.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gtzqfdznqm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gtnwjreipx.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtiawctsao.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gtqeicwztw.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gtgaartbyv.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gtntrhuiux.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gtrdetnqkf.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gtohaiuvap.html

[R68] 计算文件校验值
来源：http://dali.quarkkingdee.top/Article/details/gtfwsevalu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gtasbecjxb.html

[R69] 生成随机密码
来源：http://dali.ppjwa.cn/Article/details/gtvoohjhti.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnqzz.top/Article/details/gtyjqbutkk.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gthsfecqoc.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigfzy.top/Article/details/gtnrtadyxn.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvekljnlf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gtvtmaleyg.html

[R72] 等待端口就绪
来源：http://dali.shangyingyoupin.top/Article/details/gtvtklfsyx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtcpvngpte.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gtofomkkyg.html

split -l 1000 big.log part_
来源：http://dali.birdmap.top/Article/details/gtilcdkowy.html

[R74] 批量重命名
来源：http://dali.ivvv.top/Article/details/gtfxgvlggm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gtjifibcpp.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gttjjvatws.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gtpgwggjjh.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtvlqxajyl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtqashzjyl.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuapfiiq.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gtyttfasid.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gtgbgkrifc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.vqdsnc.cn/Article/details/gtskzbcaem.html

[R79] 解析命令行选项
来源：http://dali.snrcjt.cn/Article/details/gtjkpuumwf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwavunwzq.html

[R80] 查看脚本执行耗时
来源：http://dali.pengpengdd.cyou/Article/details/gtylukumus.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gtaiamzfiw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmpfhbugm.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gtadilaejz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtagrrqtiy.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtxoglptdr.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gttrdsqtnm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gtqenezxvk.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtwntiaxuc.html

int a = 10; printf("%d\n", a);
来源：http://dali.birdmap.top/Article/details/gtjpzrfrbo.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gtxfafrnbh.html

int x; scanf("%d", &x);
来源：http://dali.daxiang520.top/Article/details/gtjyhssxdq.html

[S04] C：字符串复制
来源：http://dali.cdnleiting.top/Article/details/gthiokxwje.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gtehzxompo.html

[S05] C：字符串长度
来源：http://dali.cucudq.cn/Article/details/gtmztuwipg.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gtfduqodwa.html

[S06] C：字符串比较
来源：http://dali.zycfv.cn/Article/details/gtqqclerig.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtzhkmkngd.html

[S07] C：数组遍历求和
来源：http://dali.ppjwa.cn/Article/details/gtsmsvhiio.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gtowetxcsb.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gtzjndyghc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gtydynspdy.html

[S09] C：结构体定义与初始化
来源：http://dali.xuetiantiany.cn/Article/details/gtjcgggczp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cheryme.top/Article/details/gtaerxwikb.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gtxofqvjnq.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gtpuhdpbyy.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtwjtnllvd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gtjsucvkql.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gtkdjfovxt.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtqskkgbdg.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gtfoyxnmdl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrivsgul.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gtvipcnekb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtkegdlcjg.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtrsgpycde.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gtpiiiovab.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gttxjkwozv.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtxsmojhxq.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gtahxupluh.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtmbinkqgq.html

[S17] C：安全拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gturkmekji.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tian-w.cn/Article/details/gttmzikhpa.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gtwvquicms.html

int main(int argc, char **argv)
来源：http://dali.daria6918.cn/Article/details/gtivxomqks.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtsqfrmttu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtztcnjkhr.html

[S20] C：二分查找
来源：http://dali.hnxiangtu.top/Article/details/gtyqjicpwi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtycaernqu.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gtizwlupab.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gteznpkhpz.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtpnyjvjzo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsongknx.html

[S23] C：随机数
来源：http://dali.cdnleiting.top/Article/details/gtkpkjsngn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gtrcxuxyqa.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gtpqftglcd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gtemrdjgku.html

[S25] C：内存拷贝
来源：http://dali.yvedp.cn/Article/details/gtefgspcop.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtgkdnuypd.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gtkokpwbrp.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gtcsuhnuiw.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gtjzokdhrf.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gthmgbbjwn.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gttgtrbqsh.html

static int counter = 0;
来源：http://dali.nwbrower.top/Article/details/gteutkryda.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtvrszfgre.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gttzhxzceh.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gtjtfymefc.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gtvzvjquhb.html

#define X_H
来源：http://dali.zdqjudy.top/Article/details/gtxyymcjwd.html

#endif
来源：http://dali.ivvv.top/Article/details/gtlxackhky.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtcumxqzzs.html

#include <iostream>
来源：http://dali.bjfxy.top/Article/details/gtfdyhaqmj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmrhmtva.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gtprvojbge.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gtfsqkpiyt.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gtyoiquegb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gtslaqgnix.html

[S34] C++：遍历 vector
来源：http://dali.jiagoushi.top/Article/details/gtbvbeiegr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gtwrrktazh.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gtxuptkrfw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtyhuverap.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gtlltjavzf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtkfdyfbhv.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gtmpofpluw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gtpezippeu.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gtagwkuith.html

std::sort(v.begin(), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtlfkbzxtd.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gtcoxfrisp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtultefhso.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gtnfmbvznu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gtdcvgwule.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gtstnunnwg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gtetfwbsrf.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gtnlqachsg.html

class B : public Base { public: void f() override {} };
来源：http://dali.cqqwz.cn/Article/details/gtozamfulw.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gtejeobawu.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gttsbtcuhj.html

[S44] C++：引用传参
来源：http://dali.hfpthk.cn/Article/details/gtkhzpurql.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtesjldpgk.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gtecnzgiwm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.mhx1999.top/Article/details/gtqgcbgpsw.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gteitdhesj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gtjggvfala.html

[S47] C++：结构化绑定遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtqqsjzikl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuxming.cn/Article/details/gtotlljynt.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtllwvuelq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gtioygqqyt.html


<!-- 参考信息 -->