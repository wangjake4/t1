代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.tianlin.xyz/Article/details/gttzvstxyc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xylfe.cn/Article/details/gtdsbleldr.html

[Q87] JSON 字段做条件
来源：http://dali.jyoumei.cn/Article/details/gtchyxtowb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwsuiskq.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtwvvytmko.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gtsupgjzjf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gtvijognsh.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gtcbnwtgyx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xinyue.icu/Article/details/gtwsvzhqey.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gteazfrhvn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gtwfwrohwy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwpvgvqtq.html

R. Bash 专题
来源：http://dali.316326.xyz/Article/details/gtbikfylsz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtahlhenki.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gtiffkuqzv.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gtjbcmweuo.html

set -euo pipefail
来源：http://dali.haohaochexian.top/Article/details/gtojyyoxen.html

[R02] 变量赋值与使用
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmoclurf.html

name="Tom"; echo "$name"
来源：http://dali.zhongyouzk.top/Article/details/gtdpolcvbb.html

[R03] 只读变量
来源：http://dali.jinqigfzy.top/Article/details/gtftqvopaf.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtxasmbdci.html

[R04] 位置参数
来源：http://dali.yuxming.cn/Article/details/gtqgsduays.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gtnxbaemlt.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gtmiotptnp.html

name="${1:-default}"
来源：http://dali.shangyingyoupin.top/Article/details/gtrpqhxfvd.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gtavakfjvv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtkgbksepr.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gtdfzclmif.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtfiznrudz.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtqxzvdjzm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gtzhnsgtsa.html

[R09] 字符串比较
来源：http://dali.meibo888.top/Article/details/gtruvoyrze.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gtfuidhgnd.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gtagqbfuwm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gtuohwkfpd.html

[R11] case 多分支
来源：http://dali.kuanghao11.cn/Article/details/gtxnnsdslw.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gtpuhdougf.html

start) echo "启动" ;;
来源：http://dali.nwbrower.top/Article/details/gtzdonrleq.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gtaiesepqx.html

*)     echo "未知命令" ;;
来源：http://dali.ehwqpu.com/Article/details/gtkcidxtzi.html

esac
来源：http://dali.guannengcc.top/Article/details/gtspnyhveh.html

[R12] for 遍历文件
来源：http://dali.hammf.cn/Article/details/gttpajlmnh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hysaishi.cn/Article/details/gtcapmilnm.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtqpofoyfp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtytmidjjs.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gtlauecspg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtyabuxicu.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtihfjnirw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gtpstjgopz.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gtfkpabchy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtvgpqibtn.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gtjneoacwx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gtejvrtffh.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gtgzhbkqru.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jyoumei.cn/Article/details/gtgierakzm.html

[R19] 数组长度
来源：http://dali.havefunace.top/Article/details/gtkmmnpput.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gtmiglxsph.html

[R20] 关联数组（字典）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedqhgcmb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gtimfppfir.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gtzquveyua.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gtmsjfvami.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtxpxrgois.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gtaqltwrwn.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtipukgeou.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gtzvxenwpt.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtwzuvnobn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ppjwa.cn/Article/details/gtypkjubov.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gtrhipwrni.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtjevpcmmn.html

[R26] 命令替换
来源：http://dali.shangyingyoupin.top/Article/details/gtxtsamzce.html

now=$(date +%F); echo "$now"
来源：http://dali.xuetiantiany.cn/Article/details/gtksrnovtk.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgjaztba.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gtuhhtdwtd.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gtqhrwmbdo.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtfbsxbmad.html

[R29] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtpiumgsup.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gttaqasiln.html

[R30] 函数返回状态码
来源：http://dali.ehwqpu.com/Article/details/gtyfiofmtb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.0kj1m.cn/Article/details/gtzvbnmbpb.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtmwqrtxhd.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gtzwuesucq.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gtsaoaqvji.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtfpitqqsp.html

[R33] 捕获错误并提示行号
来源：http://dali.chenzaomai.com/Article/details/gtyqvawttd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhoulong.xyz/Article/details/gtlyepimsx.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gtpyfojyec.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gtzlegykrt.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gtrywxecwv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gtwshemueq.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gtfjlgvcdv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ehwqpu.com/Article/details/gtgmnvplkf.html

[R37] 把输出赋给变量
来源：http://dali.shangyingyoupin.top/Article/details/gtpxuxioao.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gtavkqyamf.html

[R38] 管道串联
来源：http://dali.meibo888.top/Article/details/gtcuxvfkgw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.9152youxi.cn/Article/details/gtdggzbyaz.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gtaqumxium.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtyeigrmnl.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gtcokwvkqa.html

echo "log" >> out.log
来源：http://dali.vqdsnc.cn/Article/details/gtxaybvagr.html

[R41] 丢弃输出
来源：http://dali.9152youxi.cn/Article/details/gttkmkxurl.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtervcpghp.html

[R42] 输入重定向
来源：http://dali.jiagoushi.top/Article/details/gtrypksfzv.html

wc -l < a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtbvrxreib.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gthhkjphad.html

find . -name "*.log" -type f
来源：http://dali.gaohongyu789.top/Article/details/gtkrmykuei.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gtuhjnjqyl.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gtpohgrfsp.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gtsjmqrxkj.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtmkuafbar.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gtmijktmhq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtfmtbiyig.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gtfvjkcfrf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtkxuwrxtu.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gtblwqoznz.html

awk '{print $1, $3}' a.txt
来源：http://dali.cashguo.top/Article/details/gtvhaazzce.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gtwnhfrybm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfinxpryt.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtgiqwzexd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.havefunace.top/Article/details/gtapowoecq.html

[R51] 排序去重取前几
来源：http://dali.zhengqikj.top/Article/details/gtwgtrbwvq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gtpopfuiwm.html

[R52] 统计行数
来源：http://dali.jqgfzy.top/Article/details/gtuqbccokc.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtvzudhjbe.html

[R53] 查看文件头与实时尾
来源：http://dali.ehwqpu.com/Article/details/gtzapchida.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gtqqwgfddv.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gtczqzvpnt.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gtimwoznbp.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gtgymftbyo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xylfe.cn/Article/details/gtietdpowm.html

[R56] 远程拷贝
来源：http://dali.jiagoushi.top/Article/details/gtehcsdeqn.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtxsgbcgjd.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gttcdtlnzh.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gtmzzjgtxv.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gtbcorntqn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tian-w.cn/Article/details/gtkucicror.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtfqltrdsa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtnzlbpjtg.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtrzynsnqh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gtjmrihoft.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gtcnutncji.html

df -h;  du -sh *
来源：http://dali.dianchejie.cn/Article/details/gtugydoirg.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gtusmbfbxt.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gtwqxokapa.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gtnwqmkucp.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtjnpbjtpq.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtxevheieg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtpzvldrwa.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gtgsyaqyvj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigufen.top/Article/details/gtakpohceg.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gtsxpjexwm.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gtkdhznqlq.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtxyqbglxh.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gtwhqnxauv.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gtuspfrlpt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gtrapadafd.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gtysbszxns.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gtxfyiekhx.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gtchfkgeuv.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gtmjxdyckh.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtgapoanwi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gtzzikxpys.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gtuhpyprum.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtmcekjvxr.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gtjeesrbdp.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczfdemgn.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gtndfndwib.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gtxzeybpqb.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtcnahpbcq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gteojuvisz.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gtgeojwirz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtmgayclgo.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gtubfyayyv.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gtbbdowpba.html

[R78] 交互式菜单
来源：http://dali.jinqigfzy.top/Article/details/gtsewhdrzu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gtfbvmilhj.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gtuvgvtsha.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gtlxrajqsm.html

[R80] 查看脚本执行耗时
来源：http://dali.dianchejie.cn/Article/details/gtqpinmfjv.html

time ./run.sh
来源：http://dali.meibo888.top/Article/details/gtbhjpemgd.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcuyliqe.html

S. C / C++ 专题
来源：http://dali.yvedp.cn/Article/details/gtffzjwlus.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtkzgitpaj.html

[S01] C：Hello World
来源：http://dali.zycfv.cn/Article/details/gtwravjcja.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gtjwznjlhp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwcqiympt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gthpsxjqwm.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtitagqooc.html

[S03] C：读入整数
来源：http://dali.316326.xyz/Article/details/gtvdfspjjb.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gtnbtfgpvk.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gtttnzzbib.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.bjfxy.top/Article/details/gtaltmcmwu.html

[S05] C：字符串长度
来源：http://dali.meibo888.top/Article/details/gtmlphzhfv.html

strlen(s)
来源：http://dali.aibaodan.cn/Article/details/gtlpydxrfw.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtybgodefo.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gtrfbdyfwu.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtyqayjfrt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aibaodan.cn/Article/details/gtsubtaeqt.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gtmlstdqmb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xylfe.cn/Article/details/gtgwwuzsjm.html

[S09] C：结构体定义与初始化
来源：http://dali.dianchejie.cn/Article/details/gtscehsjon.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gtuhxbcdbw.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gtwrddbcvl.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gtlggmptgr.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtzlryhwjp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hywenlv.cn/Article/details/gtffhoncin.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gtkddhpdvk.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtubjftxdb.html

[S12] C：写文件
来源：http://dali.havefunace.top/Article/details/gtvhmypqtd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqhoepiv.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gtwurgtxjt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gtuxpdqnxv.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gttzjcwgwr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenlongwang.top/Article/details/gtzuqoxzly.html

[S15] C：类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtcbmxgqfx.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gtybbzmreo.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gthvdilbbu.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gtbzvycteu.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtacdoyfuw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gtuvqzzeze.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtqhixqjxi.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gtzedecdjt.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gtvdszaetx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtoinmexdi.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gtpehtkgvi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtkjymspuv.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gtyxticrka.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gttbeqedxl.html

[S22] C：字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gtwgobmuar.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gtfnzwnhkr.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gtgehcwnxt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gtmhtfpohh.html

[S24] C：获取本地时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxubqtce.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gtslclihwv.html

[S25] C：内存拷贝
来源：http://dali.tian-w.cn/Article/details/gttouekfbq.html

memcpy(dst, src, n);
来源：http://dali.kuanghao11.cn/Article/details/gtzftnetcw.html

[S26] C：内存清零
来源：http://dali.guowangkeji.top/Article/details/gtjpqmhctl.html

memset(a, 0, sizeof a);
来源：http://dali.dianchejie.cn/Article/details/gtsondtvgj.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gtcfcsqjsi.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtwiildrfz.html

[S28] C：静态变量
来源：http://dali.pycfn.com/Article/details/gtvezwtesu.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gtjfzxgygq.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gtzibjmloz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gaohongyu789.top/Article/details/gtsazbodtg.html

[S30] C：头文件保护
来源：http://dali.sysykeji.top/Article/details/gtjujrcqjm.html

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gtmkchnsie.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gtmzhmfygf.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpopqpti.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtmqpsfvsp.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gtjotjknup.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gtdnjfhiou.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gtcpcjuqay.html

std::string s = "hi";  s += "!";
来源：http://dali.sxryk.cn/Article/details/gtnhieyeof.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtsosvhvpg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.snrcjt.cn/Article/details/gtskorgqvz.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gtrvjuakes.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aizwys.cn/Article/details/gtqeyzqvqx.html

[S35] C++：map
来源：http://dali.chenlongwang.top/Article/details/gtuonuvyrb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtyekuemcx.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gtuasrwgio.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknjriyed.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gtubgcgaix.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtiefftbwc.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gtmoqfmyvs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvnvaqan.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gtgomiooid.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtygrrbmlp.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gtyznscmmp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnxiangtu.top/Article/details/gtqxcargto.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhbhkars.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxuanxn.top/Article/details/gtnuspxhas.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gtzjgiyvvm.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gtudjbmavs.html

[S43] C++：智能指针
来源：http://dali.yuxming.cn/Article/details/gtqmahysiu.html

auto p = std::make_unique<int>(5);
来源：http://dali.xinyue.icu/Article/details/gtgbxwhbfz.html

[S44] C++：引用传参
来源：http://dali.wangshuangyany.cn/Article/details/gtnnjcnusp.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gtscytxkjc.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtruqntovd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gtlurledjp.html

[S46] C++：函数模板
来源：http://dali.kuanghao11.cn/Article/details/gtdjzcivee.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gtbltxfebs.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gtmidzdywb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gtodmbumod.html

[S48] C++：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtknvphpmq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbagikmbo.html

while (std::getline(in, line)) { }
来源：http://dali.havefunace.top/Article/details/gtiitftswy.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gtakejnqae.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhiwuduotai.top/Article/details/gtwdljudzv.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gtppyzmbcy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gteqspanah.html

[S51] C++：显式类型转换
来源：http://dali.nanxuanxn.top/Article/details/gtemqvvjps.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gtymrtwwws.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtesbakxge.html

int size() const noexcept { return n_; }
来源：http://dali.fzhhl.top/Article/details/gtxnjnsbnv.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gtnyzzotjp.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gtoalgirdr.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gtjtbdvmjx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gtivrlbweu.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gtjydrnhrr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtuqghovxa.html

[S56] C++：optional
来源：http://dali.tian-w.cn/Article/details/gtkcxyrzzs.html


<!-- 参考信息 -->