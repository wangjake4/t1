代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.jiagoushi.top/Article/details/gtwasududi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtwivarhka.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gttjjsojrr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gtofhpvcwg.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtllfqtvjz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuanzx.com/Article/details/gtoepdutnx.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gthdjrxyjz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gtvlqrlbxk.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtgstuwbez.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jlsjyb.cn/Article/details/gtuakkurey.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gtrxoxfzli.html

[Q89] 判断表是否存在
来源：http://dali.birdmap.top/Article/details/gtjwiekouj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gttxhqhncs.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwqznrqz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gtyqlmtysp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtokkxdeas.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtcsqvkfxq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtwmhjmzcp.html

[R01] shebang 与严格模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyeistfw.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gtnheqhiii.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxdeleoj.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gtdeiwhnfa.html

name="Tom"; echo "$name"
来源：http://dali.cheryme.top/Article/details/gtdriwopwk.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gtglhzstws.html

readonly PI=3.14
来源：http://dali.yj20258888.top/Article/details/gtffaliked.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gtqfmufkle.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenjidiqi.icu/Article/details/gtzlonvzay.html

[R05] 参数默认值
来源：http://dali.hnqzz.top/Article/details/gtaciluczj.html

name="${1:-default}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzjjdzfg.html

[R06] 判断命令是否存在
来源：http://dali.xylfe.cn/Article/details/gtnsguguog.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtkuyqxnkh.html

[R07] if 判断文件
来源：http://dali.yuxming.cn/Article/details/gtpwlmfywl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtzyphugfa.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gtnlvskwxe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtkvvxkjwc.html

[R09] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtjdjeehvi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gtnxumsnon.html

[R10] 正则匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdmaqtzo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtmpubpcjs.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtcqjofsku.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtmfvsfisq.html

start) echo "启动" ;;
来源：http://dali.gzhubu.top/Article/details/gtdmlcttdn.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gtlvhbqhif.html

*)     echo "未知命令" ;;
来源：http://dali.hysaishi.cn/Article/details/gtbotbpsfw.html

esac
来源：http://dali.aibaodan.cn/Article/details/gtqnawbyar.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gtkzbisyeg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gthgxyiodu.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiegpodye.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtsgxmlnds.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gtuikvsxvb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtossicjok.html

[R15] while 逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtqfgxsnsf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.bjfxy.top/Article/details/gtnrrmtccu.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtsrdxtfvf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtycnetyyv.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gtmpknihru.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gtagsiedtg.html

[R18] 遍历数组
来源：http://dali.birdmap.top/Article/details/gtpawaicar.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhengqikj.top/Article/details/gttrchtwlp.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtbymxvyda.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gtnklhvasx.html

[R20] 关联数组（字典）
来源：http://dali.zdqjudy.top/Article/details/gtaezseqrp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtbunthiak.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gtijtnaxcv.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gtmmrkvejt.html

[R22] 截取子串
来源：http://dali.fengsongda.top/Article/details/gtcltmgxgf.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtredknmyw.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtllmgsvea.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gtlenvctaz.html

[R24] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtuzjujqji.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtmahpmqtv.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtbdjagbee.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gtwerkwkus.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gtczowxsim.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gtiuvqvgke.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gthlqfkysp.html

echo $((1 + 2 * 3))
来源：http://dali.chenzaomai.com/Article/details/gtbsikzlhe.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gtnnrnpuou.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gtgjnbczwf.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtwzzramsm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gtidbscfoi.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gthppchmsd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gtqkjqyfgp.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gtjkryxjgu.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gtilfgxury.html

[R32] 参数个数校验
来源：http://dali.yj20258888.top/Article/details/gtyuauiitj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtcqghrhgk.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gtsazxcopk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.meibo888.top/Article/details/gtqaxvvnzq.html

[R34] 退出时清理
来源：http://dali.pycfn.com/Article/details/gtrpqwxfpc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtcejkzczb.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gtslivxjzg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gtsgvuihhd.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gtozzfhxko.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gteozntqkr.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gtebboxqxi.html

files=$(ls -1)
来源：http://dali.jiagoushi.top/Article/details/gtousdpipb.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gtjeeufmcq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenzaomai.com/Article/details/gtgzrryamg.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigufen.top/Article/details/gtjcokbbvc.html

cmd > out.log 2>&1
来源：http://dali.yuanzhike.top/Article/details/gtcbawxqex.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gtolowmkpa.html

echo "log" >> out.log
来源：http://dali.yj20258888.top/Article/details/gtgvcuhigx.html

[R41] 丢弃输出
来源：http://dali.haohaochexian.top/Article/details/gtmzsbzfrd.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gtvreotbpn.html

[R42] 输入重定向
来源：http://dali.jqgufenzy.top/Article/details/gtyxmrjuvx.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gtqazjexhd.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gtaynetbsd.html

find . -name "*.log" -type f
来源：http://dali.nanxinkj.top/Article/details/gttlvtdlqg.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gtlswtpsvt.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtgbnfjfih.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gtvnncljep.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gtvygkcyrw.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gtpkljkiqe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgcjaqyn.html

[R47] sed 单行替换
来源：http://dali.sysykeji.top/Article/details/gtxxnewuld.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gthxrpcvmh.html

[R48] awk 取指定列
来源：http://dali.yuxming.cn/Article/details/gtptuvniee.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtbxjcexbt.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gttdzologc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aibaodan.cn/Article/details/gtlayhfhsm.html

[R50] awk 求和
来源：http://dali.yuanzhike.top/Article/details/gtjpzwgqxi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtyjrpnfrx.html

[R51] 排序去重取前几
来源：http://dali.nanxinkj.top/Article/details/gtkionrjya.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtodozmmgz.html

[R52] 统计行数
来源：http://dali.haohaochexian.top/Article/details/gtqsctiiap.html

wc -l a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtamnihiqk.html

[R53] 查看文件头与实时尾
来源：http://dali.mhx1999.top/Article/details/gtbljhvhxd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gtcmbyncus.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gtpydjuisx.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtzdeunxqd.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gtmnuaaqub.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gtkbinxmjj.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gtkkakyqrs.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gtzssjepuj.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gtimaqjtoy.html

ssh user@host 'uptime'
来源：http://dali.guannengcc.top/Article/details/gtqwkbutnv.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gtnwcdjxsr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gthfwyuhlg.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtqsghemki.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gtrpvyjdlf.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtahzmrgjd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.316326.xyz/Article/details/gtwxkskcpg.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gteghkjwzc.html

df -h;  du -sh *
来源：http://dali.yj202588.top/Article/details/gtygzqcekl.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtxxwcdkuc.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gtefvwextu.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gtqmuirmei.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gtjyhxurrk.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtkztstdal.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gtosjnvhac.html

[R65] 查看端口占用
来源：http://dali.aizwys.cn/Article/details/gtesyrrmrb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gtaqcfjwfv.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gtelmorrwp.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gtcbrcqrom.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtfycvcpfd.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gtauzvficb.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyodepsd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gtzapixszk.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gtrtbfrkjp.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gtdzuaakwy.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gtumwadvst.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gtcwyyxzzm.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhdwrouh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gtrxstepez.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gtomzhguvh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtptowmddg.html

[R73] 分割大日志
来源：http://dali.meibo888.top/Article/details/gtaoicinca.html

split -l 1000 big.log part_
来源：http://dali.zycfv.cn/Article/details/gtpyaehyuk.html

[R74] 批量重命名
来源：http://dali.yangfankeji.com/Article/details/gtthgqublw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlybxpvj.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtboaveqva.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.0kj1m.cn/Article/details/gtoqirrjkv.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gtbaarouwu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtcwqnmtqb.html

[R77] 读取用户输入
来源：http://dali.havefunace.top/Article/details/gtrnpslsxr.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtljrheycp.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdtpoaef.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gtislnreqo.html

[R79] 解析命令行选项
来源：http://dali.sufxvd.cn/Article/details/gtywmpwkkv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gtvnxjqhci.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gtxggtlnjv.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gtzcqtffdd.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtzjnkomnn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gtgcwdgnrr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtzstrrjdu.html

[S01] C：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtwshetuqj.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtxlotcqlw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gtvqgybqmt.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gtslgmdngi.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gtuqbuefum.html

[S03] C：读入整数
来源：http://dali.shanyushiyangtech.top/Article/details/gtirzxzrkm.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gtvzqxeadi.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gtamqbifap.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yueranfly.top/Article/details/gtlkobxsyv.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gtslmixygj.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gtpajjdkvp.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gthhihardd.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gtvdcnyyhp.html

[S07] C：数组遍历求和
来源：http://dali.hywenlv.cn/Article/details/gttbztwzch.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gtgqnpviwf.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gttqlxgrix.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.bjfxy.top/Article/details/gthjvisbxz.html

[S09] C：结构体定义与初始化
来源：http://dali.dianchejie.cn/Article/details/gtenmfadrz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwkaphhs.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtdgmgpdfk.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gtypgmghif.html

[S11] C：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtefveqbfm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gtrdqcasyl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gtptjhfwcv.html

fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtjjajwhdh.html

[S12] C：写文件
来源：http://dali.guowangkeji.top/Article/details/gtsubaessg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cashguo.top/Article/details/gtyqzhvgmw.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gttvhebsye.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sysykeji.top/Article/details/gtqcpabdus.html

[S14] C：枚举
来源：http://dali.bjfxy.top/Article/details/gtkphdjqse.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yanxiufei.cn/Article/details/gtctkuyemj.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gtotwhgjsc.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gthyuiqwxj.html

[S16] C：位操作置位
来源：http://dali.jqgfzy.top/Article/details/gtyujwoldz.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtrbtirugz.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gttuiepyce.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdpqcjlr.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtgselekhb.html

int main(int argc, char **argv)
来源：http://dali.c1oappe.top/Article/details/gtkgolxtit.html

[S19] C：快速排序
来源：http://dali.zycfv.cn/Article/details/gtjdhfomcn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gthlhnmdwf.html

[S20] C：二分查找
来源：http://dali.zycfv.cn/Article/details/gtmmwiiysz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtwsepwsjk.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gtrsewrogo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenzaomai.com/Article/details/gtnjubwgqp.html

[S22] C：字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtjpcqfcju.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gtftrnvkok.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gtravzqtrd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gthqlmzkyq.html

[S24] C：获取本地时间
来源：http://dali.yangfankeji.com/Article/details/gtamxwtdco.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gtjkhtuzhj.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gtkqsxivhp.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtmgxkwnwi.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gtyptcprep.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtnbwcpelq.html

[S27] C：定义常量
来源：http://dali.zhongyouzk.top/Article/details/gthrynodts.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtpccznjfk.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gtxsbzhqpy.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gtmftxkfmq.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gtcougewcc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daxiang520.top/Article/details/gtsvkwhtlu.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gtfdykjvxi.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gtlwakfhls.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gtiezzeflm.html

#endif
来源：http://dali.pycfn.com/Article/details/gtxbkydyjg.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gtmplxbhvx.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gtmyfmngcq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgrvphbtn.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gtfpcmaksv.html

std::string s = "hi";  s += "!";
来源：http://dali.guowangkeji.top/Article/details/gtxuqmvcjh.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gtqvdvdwzp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gtyyjngxug.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gtnptrvown.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gtthpmhcnx.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gtqzgmffgm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtixoppwqy.html

[S36] C++：unordered_map
来源：http://dali.yongpay.top/Article/details/gtryvhzcds.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtsivwzcud.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gthiwmqmax.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gtowhjybxu.html

[S38] C++：排序
来源：http://dali.meibo888.top/Article/details/gtgnnnmpvf.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtfkrlbuqt.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigufen.top/Article/details/gthdihjabm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gtvssrparu.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gtmsebdqsn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gtzxhztaoi.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gtqqwvbnos.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlimfbfkt.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gtningrdks.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnbhjkly.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gtvephczaa.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gttupdkxbh.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gtnzbjyrwe.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gtexmzdegm.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gtiijfghsr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.svipenyu.cn/Article/details/gtqsedpzxk.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gtefgdlohy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjfmobeae.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gtjjzaiptn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gtwxlnarmu.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtrwbbykts.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gttjtzogeh.html

while (std::getline(in, line)) { }
来源：http://dali.ybcxt.top/Article/details/gtyosqdyhk.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtilvqjpfi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gtjxfiymkz.html

[S50] C++：格式化数字
来源：http://dali.guowangkeji.top/Article/details/gtcoezdksd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtejhqtkpj.html

[S51] C++：显式类型转换
来源：http://dali.bjfxy.top/Article/details/gtqezntcsr.html

static_cast<double>(a) / b
来源：http://dali.smart0.xyz/Article/details/gtiudipbxy.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtzsrrtikk.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gtdzjhahdm.html

[S53] C++：移动语义
来源：http://dali.jianghu66.top/Article/details/gtznwgampg.html

std::vector<int> w = std::move(v);
来源：http://dali.xziqi.cn/Article/details/gtvajojyqs.html

[S54] C++：异常处理
来源：http://dali.shzxlz.cn/Article/details/gttgzkpuzk.html


<!-- 参考信息 -->